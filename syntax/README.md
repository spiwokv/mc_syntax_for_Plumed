Copy (as a root) `dat.syntax` to `/usr/share/mc/synthax/` and add lines:
```
file ..\*\\.(dat)$ Plumed\sCommands
include dat.syntax
```
to `/usr/share/mc/synthax/Synthax` above lines
```
file .\* unknown
include unknown.syntax
```

Alternatively (if you don't have root access) copy `dat.syntax` to `~/.local/share/mc/` and add lines:
```
file ..\*\\.(dat)$ Plumed\sCommands
include dat.syntax
```
to `~/.config/mc/mcedit/Syntax` above lines
```
file .\* unknown
include unknown.syntax
```


