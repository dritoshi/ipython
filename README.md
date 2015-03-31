ipython with scikit-learn on docker
=======================

Docker image for ipython with scikit-learn

Run
---

Run IPython Notebook server (default command).

    docker run -d -p 8080:8888 dritoshi/ipython

Run IPython Notebook server to share local file system.

    docker run -d -p 8080:8888 -v $PWD:/notebook dritoshi/ipython

Use interactive shell.

    docker run -it dritoshi/ipython ipython

Build
-----

    docker build -t dritoshi/ipython .

Copyright
-----
This software is released under the MIT License, see LICENSE.
ipython-notebook-startup.sh was originated from
[kitazaki/python34-ipython](https://github.com/skitazaki/docker-python34-ipython)
