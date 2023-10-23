<div align="center">

# asdf-starknet-foundry [![Build](https://github.com/foundry-rs/asdf-starknet-foundry/actions/workflows/build.yml/badge.svg)](https://github.com/foundry-rs/asdf-starknet-foundry/actions/workflows/build.yml) [![Lint](https://github.com/foundry-rs/asdf-starknet-foundry/actions/workflows/lint.yml/badge.svg)](https://github.com/foundry-rs/asdf-starknet-foundry/actions/workflows/lint.yml)

[Starknet Foundry] plugin for the [asdf] version manager created by [akhercha](https://github.com/akhercha).

</div>

## Install

This plugin needs `bash`, `curl`, `tar` and other generic POSIX utilities.
Everything should be included by default on your system.

```shell
asdf plugin add starknet-foundry
```

or

```shell
asdf plugin add starknet-foundry https://github.com/foundry-rs/asdf-starknet-foundry.git
```

## Use

Show all installable versions:

```shell
asdf list-all starknet-foundry
```

Install latest version:

```shell
asdf install starknet-foundry latest
```

Install specific version:

```shell
asdf install starknet-foundry 0.8.2
```

Set a version globally (in your `~/.tool-versions` file):

```shell
asdf global starknet-foundry latest
```

Set a version locally:

```shell
asdf local starknet-foundry latest
```

Now snforge and sncast commands are available:

```shell
snforge --version
```

```shell
sncast --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.

[asdf]: https://asdf-vm.com
[Starknet Foundry]: https://foundry-rs.github.io/starknet-foundry
