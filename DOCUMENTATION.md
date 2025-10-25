## `Dockerfiles`

This directory contains various Dockerfiles used to build different images for the ThereminQ project. Each Dockerfile is tailored for a specific purpose, such as running the controller, development, or specific quantum computing workloads.

*   `Dockerfile`: The main Dockerfile for the project.
*   `Dockerfile-controller`: For the WebUI controller.
*   `Dockerfile-controller-all`: A comprehensive controller.
*   `Dockerfile-cuquantum`: Includes the cuQuantum SDK.
*   `Dockerfile-dev`: For the development environment.
*   `Dockerfile-games`: For running games.
*   `Dockerfile-overlay`: An overlay Dockerfile.
*   `Dockerfile-qimcifa`: For the Qimcifa workload.
*   `Dockerfile-sieve`: For the sieve workload.
*   `Dockerfile-unittest`: For running unit tests.
*   `Dockerfile-vcl-controller-node`: For the VCL controller node.

## `buildscripts`

This directory contains scripts used to build and prepare various components of the project. These scripts handle tasks like fetching and filtering primes, building Docker images, and preparing data for quantum simulations.

*   `0-fetch-primes.sh`: Fetches prime numbers.
*   `1-filter-primes.sh`: Filters the fetched prime numbers.
*   `build_dockerfiles.sh`: Builds the Docker images from the Dockerfiles.
*   `makeqftipsy.sh`: A script for making qftipsy.
*   And many others for specific graphing and data preparation tasks.

## `configfiles`

This directory contains configuration files for various services and tools used in the project.

*   `filebeat.yml`: Configuration for Filebeat.
*   `metricbeat.yml`: Configuration for Metricbeat.
*   `passwd`: A password file.
*   `xorg.conf`: Configuration for the X server.
*   `xstartup`: A startup script for X.

## `miscfiles`

This directory contains miscellaneous files, including compressed data, logs, and other assets.

*   `TNN_d.tar.gz`: Compressed data for TNN_d.
*   `qrack output log tcc_nn36 part1 - 500.zip`: A zip file containing Qrack output logs.
*   And other compressed data files.

## `runscripts`

This directory contains a large number of scripts for running various quantum computing workloads and simulations. These scripts are designed to be executed within the Docker containers.

*   `run-cosmos`: Scripts for running cosmos workloads.
*   `run-qft`: Scripts for running QFT workloads.
*   `run-supreme`: Scripts for running supreme workloads.
*   `run-tnn`: Scripts for running TNN workloads.
*   And many other scripts for specific simulations and tests.

## `systemscripts`

This directory contains scripts for system-level tasks, such as managing swap space and VRAM. As noted in the `readme.md` in this directory, these scripts are highly specific to a particular system configuration and should be used with caution.

*   `mdadmswap.sh`: A script for managing MDADM swap.
*   `nvmeswap.sh`: A script for managing NVMe swap.
*   `vramswap.sh`: A script for managing VRAM swap.
*   And other system-level scripts.
