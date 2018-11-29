---
layout: master
---

# Visual diff tools

Meld is a visual diff and merge tool targeted at developers. Meld helps you
compare files, directories, and version controlled projects. It provides two-
and three-way comparison of both files and directories, and has support for
many popular version control systems.


## Installation on Linux

Install meld via your distribution package manager. For Debian/Ubuntu run:

```shell
$ sudo apt-get install meld
```

For Fedora:

```shell
$ sudo dnf install meld
```

Please also [verify your installation](#how-to-verify-the-installation).


## Installation on macOS

Meld is available for macOS but not officially supported yet, please follow
installation instructions from [http://meldmerge.org](http://meldmerge.org).

On macOS, there are other visual comparison tools. Please browse the net and
install your favourite one. Make sure they cooperate with Git since this often
makes comparison and conflict resolution easier.

Please also [verify your installation](#how-to-verify-the-installation).


## Installation on Windows

Please follow installation instructions from [http://meldmerge.org](http://meldmerge.org).


## How to verify the installation

To test it create two files which are similar and then compare them
with Meld or Diffuse:

```shell
$ meld file1 file2
```
