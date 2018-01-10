# docker-matlabmcr2016b

[![Build Status](https://travis-ci.org/icaoberg/docker-matlabmcr2016b.svg?branch=master)](https://travis-ci.org/icaoberg/docker-matlabmcr2016b.svg?branch=master)
[![GitHub issues](https://img.shields.io/github/issues/icaoberg/docker-matlabmcr2016b.svg)](https://github.com/icaoberg/docker-matlabmcr2016b/issues)
[![GitHub forks](https://img.shields.io/github/forks/icaoberg/docker-matlabmcr2016b.svg)](https://github.com/icaoberg/docker-matlabmcr2016b/network)
[![GitHub stars](https://img.shields.io/github/stars/icaoberg/docker-matlabmcr2016b.svg)](https://github.com/icaoberg/docker-matlabmcr2016b/stargazers)
[![GitHub license](https://img.shields.io/badge/license-GPLv3-blue.svg)](https://raw.githubusercontent.com/icaoberg/docker-matlabmcr2016b/master/LICENSE)

The [MATLAB Runtime](https://www.mathworks.com/products/compiler/matlab-runtime.html) is a standalone set of shared libraries that enables the execution of compiled MATLAB applications or components on computers that do not have MATLAB installed. When used together, MATLAB, MATLAB Compiler, and the MATLAB Runtime enable you to create and distribute numerical applications or software components quickly and securely.

To build a container using the `Dockerfile` in this repository, run the command

```
➜ docker build -t "murphylab/matlabmcr2016b" .
```

This should build a container

```
➜  docker container ls -a

CONTAINER ID        IMAGE               COMMAND                  CREATED             STATUS                        PORTS               NAMES
48dde52f2bc8        murphylab/matlabmcr2016b     "/bin/bash -c 'pyt..."   45 seconds ago      Exited (0) 39 seconds ago                         frosty_wescoff
```
