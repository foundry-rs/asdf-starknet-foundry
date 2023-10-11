<div align="center">

# asdf-starknet-foundry [![Build](https://github.com/akhercha/asdf-starknet-foundry/actions/workflows/build.yml/badge.svg)](https://github.com/akhercha/asdf-starknet-foundry/actions/workflows/build.yml) [![Lint](https://github.com/akhercha/asdf-starknet-foundry/actions/workflows/lint.yml/badge.svg)](https://github.com/akhercha/asdf-starknet-foundry/actions/workflows/lint.yml)

[starknet-foundry](https://foundry-rs.github.io/starknet-foundry/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

# Install

Plugin:

```shell
asdf plugin add starknet-foundry
# or
asdf plugin add starknet-foundry https://github.com/akhercha/asdf-starknet-foundry.git
```

starknet-foundry:

```shell
# Show all installable versions
asdf list-all starknet-foundry

# Install specific version
asdf install starknet-foundry latest

# Set a version globally (on your ~/.tool-versions file)
asdf global starknet-foundry latest

# Now starknet-foundry commands are available
snforge --version <TOOL CHECK><TOOL CHECK> sncast --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/akhercha/asdf-starknet-foundry/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Adel](https://github.com/akhercha/)
