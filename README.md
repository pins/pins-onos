# PINS ONOS Development Build Environment

Docker build environment capable of producing a version of onos and needed apps that can run with PINS.
Typically, the onos restful api would be used to include apps after onos is started.

## Build

You can locally build your apps and have the oar files copied from `local_imports/oar` into the docker build environment rather than pulling from maven.
Any oar files in this directory will be included and set to start on onos startup.  

```sh
make build
```