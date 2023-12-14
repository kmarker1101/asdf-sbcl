<div align="center">

# asdf-sbcl [![Build](https://github.com/kmarker1101/asdf-sbcl/actions/workflows/build.yml/badge.svg)](https://github.com/kmarker1101/asdf-sbcl/actions/workflows/build.yml) [![Lint](https://github.com/kmarker1101/asdf-sbcl/actions/workflows/lint.yml/badge.svg)](https://github.com/kmarker1101/asdf-sbcl/actions/workflows/lint.yml)

[sbcl](https://www.sbcl.org/getting.html) plugin for the [asdf version manager](https://asdf-vm.com).

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
asdf plugin add sbcl
# or
asdf plugin add sbcl https://github.com/kmarker1101/asdf-sbcl.git
```

sbcl:

```shell
# Show all installable versions
asdf list-all sbcl

# Install specific version
asdf install sbcl latest

# Set a version globally (on your ~/.tool-versions file)
asdf global sbcl latest

# Now sbcl commands are available
sbcl --help
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to
install & manage versions.

# Contributing

Contributions of any kind welcome! See the [contributing guide](contributing.md).

[Thanks goes to these contributors](https://github.com/kmarker1101/asdf-sbcl/graphs/contributors)!

# License

See [LICENSE](LICENSE) © [Kevin](https://github.com/kmarker1101/)
