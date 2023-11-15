<div align="center">

# asdf-knative [![Build](https://github.com/tomaszkiewicz/asdf-knative/actions/workflows/build.yml/badge.svg)](https://github.com/tomaszkiewicz/asdf-knative/actions/workflows/build.yml) [![Lint](https://github.com/tomaszkiewicz/asdf-knative/actions/workflows/lint.yml/badge.svg)](https://github.com/tomaszkiewicz/asdf-knative/actions/workflows/lint.yml)

[knative](https://github.com/tomaszkiewicz/asdf-plugin-knative) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add knative
# or
asdf plugin add knative https://github.com/tomaszkiewicz/asdf-knative.git
```

knative:

```shell
# Show all installable versions
asdf list-all knative

# Install specific version
asdf install knative latest

# Set a version globally (on your ~/.tool-versions file)
asdf global knative latest

# Now knative commands are available
kn version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tomaszkiewicz/asdf-knative/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Łukasz Tomaszkiewicz](https://github.com/tomaszkiewicz/)
