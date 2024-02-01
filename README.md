![Greenbone Logo](https://www.greenbone.net/wp-content/uploads/gb_new-logo_horizontal_rgb_small.png)

# python-project-template <!-- omit in toc -->

Python Project Template

## Table of Contents <!-- omit in toc -->

- [Requirements](#requirements)
- [Development](#development)
- [Maintainer](#maintainer)
- [License](#license)

## Requirements

Python 3.9 and later is supported.

## Development

**example** uses [poetry] for its own dependency management and build
process.

First install poetry via [pipx]

    python3 -m pipx install poetry

Afterwards run

    poetry install

in the checkout directory of **example** (the directory containing the
`pyproject.toml` file) to install all dependencies including the packages only
required for development.

Afterwards activate the git hooks for auto-formatting and linting via
[autohooks].

    poetry run autohooks activate

Validate the activated git hooks by running

    poetry run autohooks check

## Maintainer

This project is maintained by [Greenbone AG][Greenbone]

## License

Copyright (C) 2024 [Greenbone AG][Greenbone]

Licensed under the [GNU Affero General Public License v3.0 or later](LICENSE).

[Greenbone]: https://www.greenbone.net/
[poetry]: https://python-poetry.org/
[pip]: https://pip.pypa.io/
[pipx]: https://pypa.github.io/pipx/
[autohooks]: https://github.com/greenbone/autohooks
