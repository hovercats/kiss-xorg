# kiss-xorg

A repository for running Xorg on KISS Linux.

Due to the upstream repository's switch to wayland, and
my reliance on X, I forked the main repo.

Feel free to create Issues and Pull Requests for outdated software!

## Usage

Just add the directories *before* the official KISS repos in your KISS_PATH

Example:

```sh
KISS_PATH="/path/to/repo/core"
KISS_PATH="${KISS_PATH}:/path/to/kiss-xorg/extra"
KISS_PATH="${KISS_PATH}:/path/to/kiss-xorg/xorg"
KISS_PATH="${KISS_PATH}:/path/to/repo/extra"
...
```
