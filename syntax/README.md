# Instalation
Copy (as a root) `syntax/dat.syntax` to `/usr/share/mc/syntax/` and add lines:
```
file ..\*\\.(dat)$ Plumed\sCommands
include dat.syntax
```
to `/usr/share/mc/syntax/Syntax` above lines
```
file .\* unknown
include unknown.syntax
```

Alternatively (if you don't have root access) copy `syntax/dat.syntax` to `~/.local/share/mc/` or `~/.config/mc/mcedit` and add lines:
```
file ..\*\\.(dat)$ Plumed\sCommands
include dat.syntax
```
to `~/.config/mc/mcedit/Syntax` or `/.config/mc/mcedit/Syntax` above lines
```
file .\* unknown
include unknown.syntax
```
