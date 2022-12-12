# `asdf` plugin for benthos 

[![Lint][lint-badge]][lint]

## Install the plugin

```shell
asdf plugin add benthos https://github.com/benthosdev/benthos-asdf.git
```

## Install benthos

```shell
# Update the plugin
asdf plugin update benthos

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

## Example

```
~/Development/Home/benthos-asdf (main ✔) ᐅ asdf list-all benthos | tail -5
4.7.0
4.8.0
4.9.0
4.9.1
4.10.0
~/Development/Home/benthos-asdf (main ✔) ᐅ asdf install benthos 4.9.1
Benthos Installer

Website: https://www.benthos.dev
Docs: https://www.benthos.dev/docs/about
Repo: https://github.com/benthosdev/benthos

Downloading Benthos for linux/amd64...
Extracting...
Putting benthos in /home/roland/.asdf/installs/benthos/4.9.1/bin (may require password)
Version: 4.9.1
Date: 2022-10-06T14:20:52Z
Do not forget to add /home/roland/.asdf/installs/benthos/4.9.1/bin to your PATH!
Successfully installed
~/Development/Home/benthos-asdf (main ✔) ᐅ asdf global benthos 4.9.1
~/Development/Home/benthos-asdf (main ✔) ᐅ benthos --version
Version: 4.9.1
Date: 2022-10-06T14:20:52Z
~/Development/Home/benthos-asdf (main ✔) ᐅ asdf install benthos 4.10.0
Benthos Installer

Website: https://www.benthos.dev
Docs: https://www.benthos.dev/docs/about
Repo: https://github.com/benthosdev/benthos

Downloading Benthos for linux/amd64...
Extracting...
Putting benthos in /home/roland/.asdf/installs/benthos/4.10.0/bin (may require password)
Version: 4.10.0
Date: 2022-10-26T12:14:04Z
Successfully installed
~/Development/Home/benthos-asdf (main ✔) ᐅ asdf global benthos 4.10.0
~/Development/Home/benthos-asdf (main ✔) ᐅ benthos --version
Version: 4.10.0
Date: 2022-10-26T12:14:04Z
~/Development/Home/benthos-asdf (main ✔) ᐅ asdf list benthos
  4.10.0
  4.9.1
~/Development/Home/benthos-asdf (main ✔) ᐅ asdf uninstall benthos 4.9.1
~/Development/Home/benthos-asdf (main ✔) ᐅ asdf list benthos
  4.10.0
~/Development/Home/benthos-asdf (main ✔) ᐅ asdf current
benthos         4.10.0          /home/roland/.tool-versions
```

# Contributing

Contributions of any kind welcome! See the [contributing][] guide.

Thanks goes to these [contributors][]!

# License

See [LICENSE](LICENSE) © [Ashley Jeffs](https://github.com/benthosdev/)

[asdf-gh-repo]: https://github.com/asdf-vm/asdf
[asdf]: https://asdf-vm.com
[benthos]: https://benthos.dev
[contributing]: CONTRIBUTING.md
[contributors]: https://github.com/benthosdev/asdf-benthos/graphs/contributors
[lint-badge]: https://github.com/benthosdev/asdf-benthos/actions/workflows/lint.yml/badge.svg
[lint]: https://github.com/benthosdev/asdf-benthos/actions/workflows/lint.yml
