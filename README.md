<div align="center">

# asdf-kof [![Build](https://github.com/alvesgabriel/asdf-kof/actions/workflows/build.yml/badge.svg)](https://github.com/alvesgabriel/asdf-kof/actions/workflows/build.yml) [![Lint](https://github.com/alvesgabriel/asdf-kof/actions/workflows/lint.yml/badge.svg)](https://github.com/alvesgabriel/asdf-kof/actions/workflows/lint.yml)

[kof](https://koflang.github.io/docs) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add kof
# or
asdf plugin add kof https://github.com/alvesgabriel/asdf-kof.git
```

kof:

```shell
# Show all installable versions
asdf list-all kof

# Install specific version
asdf install kof latest

# Set a version globally (on your ~/.tool-versions file)
asdf global kof latest

# Now kof commands are available
kof version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/alvesgabriel/asdf-kof/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Gabriel Alves](https://github.com/alvesgabriel/)
