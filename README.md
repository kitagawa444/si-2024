# sice-si-template
[![Build Status](https://travis-ci.org/jsk-report-template/si-template.svg?branch=master)](https://travis-ci.org/github/jsk-report-template/si-template)

Latex template for SICE-SI

### 1. Prerequisities

```bash
# only for ubuntu 12.04
$ sudo apt-add-repository ppa:texlive-backports/ppa
$ sudo apt-get update
$ sudo apt-get install lsb-release
```

### 2. Edit LaTeX files

### 3. Make pdf

```bash
$ make
```

### Optional. Convert Japanese punctuations

```bash
$ make pub
# or
$ make publish
# will convert 「、」「。」 to 「，」「．」 in *.tex
# Original files are backed up as *.tex.orig
```

### Optional. cleaning

```bash
$ make clean
# or
$ make wipe
```
