<div align="center">

# asdf-azurite [![Build](https://github.com/connorwagner/asdf-azurite/actions/workflows/build.yml/badge.svg)](https://github.com/connorwagner/asdf-azurite/actions/workflows/build.yml) [![Lint](https://github.com/connorwagner/asdf-azurite/actions/workflows/lint.yml/badge.svg)](https://github.com/connorwagner/asdf-azurite/actions/workflows/lint.yml)

[azurite](https://github.com/Azure/Azurite) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add azurite
# or
asdf plugin add azurite https://github.com/connorwagner/asdf-azurite.git
```

azurite:

```shell
# Show all installable versions
asdf list-all azurite

# Install specific version
asdf install azurite latest

# Set a version globally (on your ~/.tool-versions file)
asdf global azurite latest

# Now azurite commands are available
azurite --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/connorwagner/asdf-azurite/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Connor Wagner](https://github.com/connorwagner/)
