<div align="center">

# asdf-infisical

[infisical](https://infisical.com/docs/cli/overview) plugin for the [asdf version manager](https://asdf-vm.com).

</div>

# Contents

- [Dependencies](#dependencies)
- [Install](#install)
- [License](#license)

# Dependencies

- `bash`, `curl`, `tar`, `git`, and [POSIX utilities](https://pubs.opengroup.org/onlinepubs/9699919799/idx/utilities.html).

# Install

Plugin:

```shell
asdf plugin add infisical https://github.com/gustavorps/asdf-infisical.git
```

infisical:

```shell
# Show all installable versions
asdf list-all infisical

# Install specific version
asdf install infisical latest

# Set a version for the current directory
asdf set infisical latest

# Now infisical commands are available
infisical --version
```

Check [asdf](https://github.com/asdf-vm/asdf) readme for more instructions on how to install & manage versions.

# License

See [LICENSE](LICENSE)
