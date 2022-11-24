![Greenbone Logo](https://www.greenbone.net/wp-content/uploads/gb_new-logo_horizontal_rgb_small.png)

# FIXME: Python Project Template <!-- omit in toc -->

FIXME: This repository contains template files for new python projects

## Table of Contents <!-- omit in toc -->

- [Documentation](#documentation)
- [Installation](#installation)
  - [Version](#version)
  - [Requirements](#requirements)
  - [Install using pip](#install-using-pip)
- [Example](#example)
- [Support](#support)
- [Maintainer](#maintainer)
- [Contributing](#contributing)
- [License](#license)

## Documentation

FIXME: Link to documentation or documentation here

## Installation

FIXME: Put a link to installation guide or INSTALL.md, or short install description

### Requirements

FIXME: Python 3.7 and later is supported.

## Support

For any question on the usage of <FIXME> please use the
[Greenbone Community Portal](https://community.greenbone.net/c/gmp). If you
found a problem with the software, please
[create an issue](https://github.com/greenbone/gvm-tools/issues)
on GitHub.

## Maintainer

This project is maintained by [Greenbone Networks GmbH](https://www.greenbone.net/).

## Contributing

Your contributions are highly appreciated. Please
[create a pull request](https://github.com/greenbone/python-gvm/pulls) on GitHub.
For bigger changes, please discuss it first in the
[issues](https://github.com/greenbone/python-gvm/issues).

For development you should use [poetry](https://python-poetry.org)
to keep you python packages separated in different environments. First install
poetry via pip

```shell
python3 -m pip install --user poetry
```

Afterwards run

```shell
poetry install
```

in the checkout directory of python-gvm (the directory containing the
`pyproject.toml` file) to install all dependencies including the packages only
required for development.

The python-gvm repository uses [autohooks](https://github.com/greenbone/autohooks)
to apply linting and auto formatting via git hooks. Please ensure the git hooks
are active.

    $ poetry install
    $ poetry run autohooks activate --force

## License

Copyright (C) 2022 [Greenbone Networks GmbH](https://www.greenbone.net/)

Licensed under the [GNU General Public License v3.0 or later](LICENSE).
