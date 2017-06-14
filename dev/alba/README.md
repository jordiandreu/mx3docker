# mx3docker
Docker file + startup script for MXCuBE 2 at ALBA

The docker mounts your local copy of the MXCuBE repository through a shared mounted directory.

## Building the docker image

    docker build -t mx3_deb9_alba .

## Before starting:

Set environment variable, e.g. (in ~/.bashrc for bash):

    export MXCUBE2_ROOT=/path/to/dir/containing/mxcube/repository


## Running the container
Execute the `start_mxcube2` script to run the right docker command line with required options:

    ./start_mxcube2

This will prompt you to the the working directory inside the clean docker container.

