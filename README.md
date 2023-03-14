<div align="center">

# asdf-emacs [![Build](https://github.com/mimikun/asdf-emacs/actions/workflows/build.yml/badge.svg)](https://github.com/mimikun/asdf-emacs/actions/workflows/build.yml) [![Lint](https://github.com/mimikun/asdf-emacs/actions/workflows/lint.yml/badge.svg)](https://github.com/mimikun/asdf-emacs/actions/workflows/lint.yml)


[emacs](https://www.gnu.org/software/emacs/) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add emacs
# or
asdf plugin add emacs https://github.com/mimikun/asdf-emacs.git
```

emacs:

```shell
# Show all installable versions
asdf list-all emacs

# Install specific version
asdf install emacs latest

# Set a version globally (on your ~/.tool-versions file)
asdf global emacs latest

# Now emacs commands are available
emacs --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](CONTRIBUTING.md).

[Thanks goes to these contributors](https://github.com/mimikun/asdf-emacs/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [mimikun](https://github.com/mimikun/)
