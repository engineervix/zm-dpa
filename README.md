# The Data Protection Act, 2021

> An Act to provide an effective system for the use and protection of personal data; regulate the collection, use, transmission, storage and otherwise processing of personal data; establish the Office of the Data Protection Commissioner and provide for its functions; the registration of data controllers and licencing of data auditors; provide for the duties of data controllers and data processors; provide for the rights of data subjects; and provide for matters connected with, or incidental to, the foregoing.
>
> Source: <https://www.parliament.gov.zm/node/8853>

[![Continuous Integration](https://github.com/engineervix/zm-dpa/actions/workflows/main.yml/badge.svg)](https://github.com/engineervix/zm-dpa/actions/workflows/main.yml)
[![python3](https://img.shields.io/badge/python-3.12-brightgreen.svg)](https://python.org/)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![Conventional Changelog](https://img.shields.io/badge/changelog-conventional-brightgreen.svg)](https://github.com/conventional-changelog)
[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-yellow.svg)](https://conventionalcommits.org)

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->

- [Introduction](#introduction)
  - [Why This Project Exists](#why-this-project-exists)
- [Development](#development)
  - [First things first](#first-things-first)
  - [Getting Started](#getting-started)
- [Contributing](#contributing)
- [TODO](#todo)
- [Notice](#notice)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->

## Introduction

Powered by [MkDocs](https://www.mkdocs.org/), this project transforms a traditionally dense and difficult to navigate PDF of the aforementioned _Act_ into an easily navigable, searchable, and visually appealing online resource.

### Why This Project Exists

Navigating legislative documents can be daunting and often results in a headache. This project was born out of the desire to make the process of understanding the _Act_ more approachable and less painful.

## Development

### First things first

You need to have [Python 3.12](https://www.python.org/) and [Poetry](https://python-poetry.org/) installed on your machine. If, for some reason, you have a different python version, you can use [pyenv](https://github.com/pyenv/pyenv) to install multiple python versions on your machine. Once you have Python 3.12 installed, create a [**virtual environment**](https://realpython.com/python-virtual-environments-a-primer/).

### Getting Started

Here, we assume that you have `git` on your machine, and that you have created a Python 3.12 virtual environment.

Now, upon cloning this repository (or forking + cloning your fork), navigate to the cloned project directory.

1. In your [**virtual environment**](https://realpython.com/python-virtual-environments-a-primer/), install Python dependencies

   ```bash
   poetry install
   ```

2. Run the following in your shell:

   ```bash
   mkdocs serve
   ```

   The documentation will be available at: <http://127.0.0.1:8001/>

## Contributing

<!-- Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)): -->

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions are most welcome! A good place to start is by helping out with the unchecked items in the [TODO](#todo) section of this README!

Feel free to check the [issues page](https://github.com/engineervix/zm-dpa/issues) and take a look at the [contributing guide](https://github.com/engineervix/zm-dpa/blob/main/CONTRIBUTING) before you get started.

## TODO

- [ ] where reference is made to other sections, use hyperlinks to link to those sections

## Notice

I do not own the copyright to the contents of the aforementioned _Act_. The text of the _Act_ is a public document, and this project aims to make it more accessible and user-friendly. Any modifications or enhancements to the presentation are my own work, and permission is granted to copy, distribute and/or modify this work under the terms of the GNU Free Documentation License as published by the Free Software Foundation, either version 1.3, or (at your option) any later version; with no Invariant Sections, no Front-Cover Texts and no Back-Cover Texts. A copy of the license is contained in the file `COPYING`.

---