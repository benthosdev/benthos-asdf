<div align="center">

# asdf-benthos [![Build](https://github.com/benthosdev/asdf-benthos/actions/workflows/build.yml/badge.svg)](https://github.com/benthosdev/asdf-benthos/actions/workflows/build.yml) [![Lint](https://github.com/benthosdev/asdf-benthos/actions/workflows/lint.yml/badge.svg)](https://github.com/benthosdev/asdf-benthos/actions/workflows/lint.yml)


[benthos](https://benthos.dev) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add benthos
# or
asdf plugin add benthos https://github.com/benthosdev/asdf-benthos.git
```

benthos:

```shell
# Show all installable versions
asdf list-all benthos

# Install specific version
asdf install benthos latest

# Set a version globally (on your ~/.tool-versions file)
asdf global benthos latest

# Now benthos commands are available
benthos --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/benthosdev/asdf-benthos/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ashley Jeffs](https://github.com/benthosdev/)
