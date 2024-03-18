# What Provides this file?

A single bash script, which can identify what package (and package manager) provides a specific file.

## Usage

`./whatprovides [file | executable]`

If an executable is provided, `which` is used to look up the absolute path of the executable.

## Supported Package Managers

Right now, this script only supports a couple package managers, but I would like to add more.
The challenge for me, is I don't use any other package managers, so I cannot test any implementation.

- XBPS (Void Linux package manager)
- Apt (Debian, Ubuntu, and Derivatives)
- Pip (Python packages)

If you would like to contribute a new package manager, please post a PR.
