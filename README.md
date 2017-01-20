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

## Contact and Copyright
All files in this repository are Copyright 2016, Keith Sharp.  They are
licensed under the GNU GPL Version 3.  If you have got any questions, drop an
email to [<kms@passback.co.uk>](mailto:kms@passback.co.uk).
