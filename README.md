# Ruby (SCL) S2I Docker images

[![Build Status](https://travis-ci.org/ausnimbus/s2i-ruby-scl.svg?branch=master)](https://travis-ci.org/ausnimbus/s2i-ruby-scl)

This repository contains the source for building various versions of
the Ruby application as a reproducible Docker image
[source-to-image](https://github.com/openshift/source-to-image)
to be run on [AusNimbus](https://www.ausnimbus.com.au/).

Images are built with Ruby RPM packages from SCL.
The resulting image can be run using [Docker](http://docker.io).

## Versions

The versions currently supported are:

- 2.0 (deprecated)
- 2.2
- 2.3
