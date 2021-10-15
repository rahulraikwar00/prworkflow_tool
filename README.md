# GitHub CLI

`pwr` is Pull Requests Workflow on the command line. It brings OPEN, CLOSED,MERGED and other PR concepts to the terminal next to where you are already working with `git` and your code.


![Screenshot](https://i.imgur.com/wdRz0nL.png)


prw is available for repositories hosted on GitHub.com, and to install on macOS, Windows, and Linux.

## Contributing

If anything feels off, or if you feel that some functionality is missing, feel free to contribute 👍

<!-- this anchor is linked to from elsewhere, so avoid renaming it -->
## Installation

### Linux

| Install:            | Run:            |
| ------------------- | --------------------|
| `bash install.sh` | `Python prw.py --help`
||`python prw.py auth <token>`

<i>It does not have a specialized `upgrade` command yet, but the `install` command should work for upgrading to a newer version of GitHub prw.</i>

## available commands
- `auth <token> `
- `repo <username/repo_name> [options] [mode] `
