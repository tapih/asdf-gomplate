<div align="center">

# asdf-gomplate [![Build](https://github.com/tapih/asdf-gomplate/actions/workflows/build.yml/badge.svg)](https://github.com/tapih/asdf-gomplate/actions/workflows/build.yml) [![Lint](https://github.com/tapih/asdf-gomplate/actions/workflows/lint.yml/badge.svg)](https://github.com/tapih/asdf-gomplate/actions/workflows/lint.yml)

[gomplate](https://github.com/hairyhenderson/gomplate) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add gomplate
# or
asdf plugin add gomplate https://github.com/tapih/asdf-gomplate.git
```

gomplate:

```shell
# Show all installable versions
asdf list-all gomplate

# Install specific version
asdf install gomplate latest

# Set a version globally (on your ~/.tool-versions file)
asdf global gomplate latest

# Now gomplate commands are available
gomplate --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/tapih/asdf-gomplate/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Hiroshi Muraoka](https://github.com/tapih/)
