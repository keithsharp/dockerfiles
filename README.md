# My Dockerfiles Collection
This repository contains the Dockerfiles that I use for various
odds and ends.

* Python 3 - creates a simple Python 3 environment with PIP installed:

    docker build --rm -t <username>/python3 .
    docker run -ti --rm -v ./src:/src <username>/python3

## Contact and Copyright
All files in this repository are Copyright 2016, Keith Sharp.  They are
licenced under the GNU GPL Version 3.  If you have got any questions, drop an
email to [<kms@passback.co.uk>](mailto:kms@passback.co.uk).
