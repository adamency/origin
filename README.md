
# Origin

Package Management Detective

Gather package management info for a command or a file and print its estimated origin among manually installed packages.

## Installation

```
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
