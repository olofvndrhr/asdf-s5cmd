<div align="center">

# asdf-s5cmd [![Build](https://github.com/olofvndrhr/asdf-s5cmd/actions/workflows/build.yml/badge.svg)](https://github.com/olofvndrhr/asdf-s5cmd/actions/workflows/build.yml) [![Lint](https://github.com/olofvndrhr/asdf-s5cmd/actions/workflows/lint.yml/badge.svg)](https://github.com/olofvndrhr/asdf-s5cmd/actions/workflows/lint.yml)

[s5cmd](https://github.com/peak/s5cmd) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `gzip` and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add s5cmd
# or
asdf plugin add s5cmd https://github.com/olofvndrhr/asdf-s5cmd.git
```

s5cmd:

```shell
# Show all installable versions
asdf list all s5cmd

# Install specific version
asdf install s5cmd latest

# Set a version globally (on your ~/.tool-versions file)
asdf set --home s5cmd latest

# Now s5cmd commands are available
s5cmd version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/olofvndrhr/asdf-s5cmd/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Ivan Schaller](https://github.com/olofvndrhr/)
