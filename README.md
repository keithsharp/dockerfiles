# My Dockerfiles Collection
This repository contains the Dockerfiles that I use for various
odds and ends.

* [Python 2](https://github.com/keithsharp/dockerfiles/tree/master/Python2) - creates a simple Python 2 environment with PIP installed:
```shell
docker build --rm -t <username>/python2 .
docker run -ti --rm -v ./src:/src <username>/python2
```

* [Python 3](https://github.com/keithsharp/dockerfiles/tree/master/Python3) - creates a simple Python 3 environment with PIP installed:
```shell
docker build --rm -t <username>/python3 .
docker run -ti --rm -v ./src:/src <username>/python3
```

* [C++](https://github.com/keithsharp/dockerfiles/tree/master/Cpp) - creates a simple C++ development environment with g++, clang++, and cmake installed:
```shell
docker build --rm -t <username>/cpp .
docker run -ti --rm -v ./src:/src <username>/cpp
```

* [Packer](https://github.com/keithsharp/dockerfiles/tree/master/Packer) - creates a tiny container with only the [Packer](https://packer.io) binary installed:
```shell
docker build --rm -t <username>/packer .
docker run -ti --rm <username>/packer
```

* [Pandoc](https://github.com/keithsharp/dockerfiles/tree/master/Pandoc) - creates a container based on [Fedora](https://getfedora.org) 26 with [Pandoc](https://www.pandoc.org), [Texlive](https://www.tug.org/texlive/), and [Make](https://www.gnu.org/software/make/) installed for document processing:
```shell
docker build --rm -t <username>/pandoc .
docker run -ti --rm -v ./src:/src <username>/pandoc /bin/bash
```

## Contact and Copyright
All files in this repository are Copyright 2016, Keith Sharp.  They are
licensed under the GNU GPL Version 3.  If you have got any questions, drop an
email to [<kms@passback.co.uk>](mailto:kms@passback.co.uk).
