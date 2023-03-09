<div align="center">

# asdf-teller [![Build](https://github.com/pdemagny/asdf-teller/actions/workflows/build.yml/badge.svg)](https://github.com/pdemagny/asdf-teller/actions/workflows/build.yml) [![Lint](https://github.com/pdemagny/asdf-teller/actions/workflows/lint.yml/badge.svg)](https://github.com/pdemagny/asdf-teller/actions/workflows/lint.yml)


[teller](https://github.com/tellerops/teller) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`: generic POSIX utilities.

# Install

Plugin:

```shell
asdf plugin add teller
# or
asdf plugin add teller https://github.com/pdemagny/asdf-teller.git
```

teller:

```shell
# Show all installable versions
asdf list-all teller

# Install specific version
asdf install teller latest

# Set a version globally (on your ~/.tool-versions file)
asdf global teller latest

# Now teller commands are available
teller --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/pdemagny/asdf-teller/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Pierre Demagny](https://github.com/pdemagny/)
