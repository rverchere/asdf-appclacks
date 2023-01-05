<div align="center">

# asdf-appclacks [![Build](https://github.com/rverchere/asdf-appclacks/actions/workflows/build.yml/badge.svg)](https://github.com/rverchere/asdf-appclacks/actions/workflows/build.yml) [![Lint](https://github.com/rverchere/asdf-appclacks/actions/workflows/lint.yml/badge.svg)](https://github.com/rverchere/asdf-appclacks/actions/workflows/lint.yml)


[appclacks](https://www.doc.appclacks.com/index.html) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add appclacks
# or
asdf plugin add appclacks https://github.com/rverchere/asdf-appclacks.git
```

appclacks:

```shell
# Show all installable versions
asdf list-all appclacks

# Install specific version
asdf install appclacks latest

# Set a version globally (on your ~/.tool-versions file)
asdf global appclacks latest

# Now appclacks commands are available
appclacks --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/rverchere/asdf-appclacks/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Rémi Verchère](https://github.com/rverchere/)
