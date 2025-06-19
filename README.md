<div align="center">

# asdf-bkl [![Build](https://github.com/fredsmith/asdf-bkl/actions/workflows/build.yml/badge.svg)](https://github.com/fredsmith/asdf-bkl/actions/workflows/build.yml) [![Lint](https://github.com/fredsmith/asdf-bkl/actions/workflows/lint.yml/badge.svg)](https://github.com/fredsmith/asdf-bkl/actions/workflows/lint.yml)

[bkl](https://bkl.gopatchy.io/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add bkl
# or
asdf plugin add bkl https://github.com/fredsmith/asdf-bkl.git
```

bkl:

```shell
# Show all installable versions
asdf list-all bkl

# Install specific version
asdf install bkl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global bkl latest

# Now bkl commands are available
bkl --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/fredsmith/asdf-bkl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Fred Smith](https://github.com/fredsmith/)
