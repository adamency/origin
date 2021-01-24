## Donations

If my work helped you, please consider chipping in at: https://www.patreon.com/adamency

My most sincere thanks.

# Origin

~~ Package Management Detective ~~

Gather package management info for a command or a file and print its estimated origin among manually installed packages.

## Installation

```
mkdir -p ~/.local/bin
cp origin ~/.local/bin/
chmod +x ~/.local/bin/origin 
```

If the directory `~/.local/bin` is not in `$PATH`, add this line in `~/.profile` or `~/.bash_profile` (to be available everywhere):

```
PATH="$HOME/.local/bin:$PATH"
```

or this line in `~/.bashrc` (to be available only in interactive shells):

```
export PATH="$HOME/.local/bin:$PATH"
```

Source the modified file. or open a new terminal, or log-out and log-in to your account for the change to take effect.

## Usage Guide

#### Command

`origin <command>` will print the absolute (real) path of the command, the package providing it, and an estimation of the reason why the package is present on the system.


#### File

`origin <file>` will print the absolute (real) path of the file , the package providing it, and an estimation of the reason why the package is present on the system.
