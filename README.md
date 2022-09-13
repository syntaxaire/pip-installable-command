# Minimal installable command-line tool

This repository demonstrates the minimum needed to install a
command-line utility to the PATH using `pip`. It uses poetry
as the build system and demonstrates usage of a tag for
version control of the tool. poetry does not need to be installed
on the target system; its build component will be automatically
acquired as a build dependency by pip.

These instructions assume that `python` and `pip` are already
present on the system PATH environment variable, or active in
the PATH of a virtual environment.

## Installation
`pip install git+https://github.com/syntaxaire/pip-installable-command@v1.0`

## Usage
`test-cli`

## Uninstallation
`pip uninstall test-cli`
