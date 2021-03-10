# NRT-IMPACTS_Frontiers
Source code repository for NRT-IMPACTS Frontiers in Plant Science (CSS 844) at Michigan State University

## Initializing submodules
Most of the code in this repository is held within external git repositories via git submodules. This means that you must pull code from each submodule.

### Pulling code from ALL submodules for the first time
Warning: this may take a long time, since some submodules have large data files associated with them. Use the command:
```
git submodule update --init --recursive
```

### Updating code from ALL submodules
```
git submodule update --recursive --remote
```

### Pulling code from a SINGLE submodule for the first time
```
git submodule update --init --remote -- path/to/submodule
```
Make sure that the submodule path does not have a trailing '/'.

### Updating code from a SINGLE submodule
```
git submodule update --remote -- path/to/submodule
```
Make sure that the submodule path does not have a trailing '/'.

