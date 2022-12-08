<div align="center">

# asdf-vhs [![Build](https://github.com/chessmango/asdf-vhs/actions/workflows/build.yml/badge.svg)](https://github.com/chessmango/asdf-vhs/actions/workflows/build.yml) [![Lint](https://github.com/chessmango/asdf-vhs/actions/workflows/lint.yml/badge.svg)](https://github.com/chessmango/asdf-vhs/actions/workflows/lint.yml)


[vhs](https://github.com/charmbracelet/vhs) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Why?](#why)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add vhs https://github.com/chessmango/asdf-vhs.git
```

vhs:

```shell
# Show all installable versions
asdf list-all vhs

# Install specific version
asdf install vhs latest

# Set a version globally (on your ~/.tool-versions file)
asdf global vhs latest

# Now vhs commands are available
vhs --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/chessmango/asdf-vhs/graphs/contributors)!

# License

See [LICENSE](LICENSE)
