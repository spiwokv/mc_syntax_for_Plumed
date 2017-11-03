# mc_syntax_for_Plumed
Syntax highlight of plumed.dat files in Midnight Commander

![alt text][./screenshot.png]

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

Alternatively (if you don't have root access) copy `syntax/dat.syntax` to `~/.local/share/mc/` and add lines:
```
file ..\*\\.(dat)$ Plumed\sCommands
include dat.syntax
```
to `~/.config/mc/mcedit/Syntax` above lines
```
file .\* unknown
include unknown.syntax
```


