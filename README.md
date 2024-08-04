## FS-Formatter

The FS-Formatter repository is a **UNIX file system** inspired tree structure automator.
With FS-Formatter it is possible to make boring structures look nice.

<img src='https://raw.githubusercontent.com/antonsimmerle/FS-Formatter/master/resources/0.png' width="500"/>

> To step higher into the hierarchy you continuously add one **space**

FS-Formatter was finished 28-12-23 by Anton Simmerle.

### Requirements: 📋
* GCC (GNU Compiler Collection)
* Standard C Library (libc)

### Compatibility: 🌐
FS-Formatter uses only standard C libraries such as 'stdio.h' and 'stdlib.h', so it should be compatible with UNIX and non UNIX systems.

### Limits: 🔒
FS-Formatter uses non-exponential dynamic memory allocation for the amount of nodes as well as the depth of the nodes, but falls back to fixed sized arrays for the length of the text of the node (1024 characters).

### Usage: ⚙️
```bash
gcc -o main main.c
./main <input.txt>
```