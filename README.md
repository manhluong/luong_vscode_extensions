### List of my used VSCode extensions

This is a list with the VSCode extensions that I am currently using.

It is here only as a simple way to share the extensions across laptops.

Command used to generate the list:

code --list-extensions | xargs -L 1 echo code --install-extension

The list is then saved in a script to be run after adding `code` to the PATH.

---

## Usage

sh install_vscode_extensions.sh

