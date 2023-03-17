<div align="center">

# asdf-opensearch-cli [![Build](https://github.com/iul1an/asdf-opensearch-cli/actions/workflows/build.yml/badge.svg)](https://github.com/iul1an/asdf-opensearch-cli/actions/workflows/build.yml) [![Lint](https://github.com/iul1an/asdf-opensearch-cli/actions/workflows/lint.yml/badge.svg)](https://github.com/iul1an/asdf-opensearch-cli/actions/workflows/lint.yml)


[opensearch-cli](https://opensearch.org/docs/latest/tools/cli/) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents
- [Compatibility](#compatibility)
- [Install](#install)
- [Contributing](#contributing)
- [License](#license)

# Compatibility
This plugin works with Linux and MacOS, both amd64 and arm64 CPU architecture.

# Install

Plugin:

```shell
asdf plugin add opensearch-cli
# or
asdf plugin add opensearch-cli https://github.com/iul1an/asdf-opensearch-cli.git
```

opensearch-cli:

```shell
# Show all installable versions
asdf list-all opensearch-cli

# Install specific version
asdf install opensearch-cli latest

# Set a version globally (on your ~/.tool-versions file)
asdf global opensearch-cli latest

# Now opensearch-cli commands are available
opensearch-cli --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/iul1an/asdf-opensearch-cli/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Iulian Mandache](https://github.com/iul1an/)
