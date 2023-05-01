<div align="center">

# asdf-hostctl [![Build](https://github.com/svenluijten/asdf-hostctl/actions/workflows/build.yml/badge.svg)](https://github.com/svenluijten/asdf-hostctl/actions/workflows/build.yml) [![Lint](https://github.com/svenluijten/asdf-hostctl/actions/workflows/lint.yml/badge.svg)](https://github.com/svenluijten/asdf-hostctl/actions/workflows/lint.yml)


[hostctl](https://github.com/guumaster/hostctl) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add hostctl
# or
asdf plugin add hostctl https://github.com/svenluijten/asdf-hostctl.git
```

hostctl:

```shell
# Show all installable versions
asdf list-all hostctl

# Install specific version
asdf install hostctl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global hostctl latest

# Now hostctl commands are available
hostctl --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/svenluijten/asdf-hostctl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Sven Luijten](https://github.com/svenluijten/)
