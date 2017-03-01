# Optional Subtree History

As the name says this repository offers the flexibility to optionally save a different bash history per subtree in the directory structure.
In other words you can have a different bash history for different projects.

Inspired by https://gist.github.com/leipzig/1651133

# Installation

In order to install this git do the following:

```bash
$ git clone https://github.com/van51/subtree_history.git
$ cd subtree_history
$ chmod +x ./install.sh
$ ./install.sh
```

# Usage

In order to initialize a "local" history in a subtree starting at the directory *foo*, you can do one of the following:

```bash
$ local_dir_history /path/to/foo
```
or
```bash
$ cd /path/to/foo
$ local_dir_history
