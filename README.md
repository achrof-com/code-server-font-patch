# Code Server Font Patch

This patchs [code-server](https://github.com/cdr/code-server) to enable load fonts [Hack Nerd Font](https://github.com/ryanoasis/nerd-fonts/releases/download/v3.2.1/Hack.zip) in server.

## Installation

- Clone this repository.

```bash
git clone https://github.com/achrof-com/code-server-font-patch.git
cd code-server-font-patch
```

- Run this command (change `path-to-code-server` to your code-server path, leave it empty if you install code-server from installer or code-server is in `/usr/lib/code-server`):

```bash
sudo ./patch.sh [path-to-code-server]
```

## Settings

You may need to set font family in code-server settings:

```
"editor.fontFamily": "'Hack Nerd Font', Consolas, 'Courier New', monospace",
"terminal.integrated.fontFamily": "'Hack Nerd Font', Consolas, 'Courier New', monospace",
```
