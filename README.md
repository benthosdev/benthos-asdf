# `asdf` plugin for benthos 

[![Build][build-badge]][build]
[![Lint][lint-badge]][lint]

[benthos][] plugin for the [asdf][] version manager.

## Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

## Dependencies

**TODO: adapt this section**

- `bash`, `curl`, `tar`: generic POSIX utilities.
- `SOME_ENV_VAR`: set this environment variable in your shell config to load the correct version of tool x.

## Install the plugin

```shell
asdf plugin add benthos

# ... or ...
asdf plugin add benthos https://github.com/benthosdev/benthos-asdf.git
```

## Install benthos

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

Check the [asdf][asdf-gh-repo] README for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing][] guide.

Thanks goes to these [contributors][]!

# License

See [LICENSE](LICENSE) © [Ashley Jeffs](https://github.com/benthosdev/)

[asdf-gh-repo]: https://github.com/asdf-vm/asdf
[asdf]: https://asdf-vm.com
[benthos]: https://benthos.dev
[build-badge]: https://github.com/benthosdev/asdf-benthos/actions/workflows/build.yml/badge.svg
[build]: https://github.com/benthosdev/asdf-benthos/actions/workflows/build.yml
[contributing]: CONTRIBUTING.md
[contributors]: https://github.com/benthosdev/asdf-benthos/graphs/contributors
[lint-badge]: https://github.com/benthosdev/asdf-benthos/actions/workflows/lint.yml/badge.svg
[lint]: https://github.com/benthosdev/asdf-benthos/actions/workflows/lint.yml
