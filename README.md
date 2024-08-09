<div align="center">

# asdf-protoc-gen-swift [![Build](https://github.com/currentjeff/asdf-protoc-gen-swift/actions/workflows/build.yml/badge.svg)](https://github.com/currentjeff/asdf-protoc-gen-swift/actions/workflows/build.yml) [![Lint](https://github.com/currentjeff/asdf-protoc-gen-swift/actions/workflows/lint.yml/badge.svg)](https://github.com/currentjeff/asdf-protoc-gen-swift/actions/workflows/lint.yml)

[protoc-gen-swift](https://github.com/currentjeff/asdf-protoc-gen-swift) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add protoc-gen-swift
# or
asdf plugin add protoc-gen-swift https://github.com/currentjeff/asdf-protoc-gen-swift.git
```

protoc-gen-swift:

```shell
# Show all installable versions
asdf list-all protoc-gen-swift

# Install specific version
asdf install protoc-gen-swift latest

# Set a version globally (on your ~/.tool-versions file)
asdf global protoc-gen-swift latest

# Now protoc-gen-swift commands are available
protoc-gen-swift --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/currentjeff/asdf-protoc-gen-swift/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Jeff Moran](https://github.com/currentjeff/)
