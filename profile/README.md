# Embedded Containers

An ecosystem of containerized tools for Embedded development. An example would be a performance-optimized OCI container image (aka Docker) for building embedded applications.

The initial focus will be for the [Zephyr RTOS](https://www.zephyrproject.org/) but may expand to other embedded software systems over time.

## Zephyr RTOS

The main project can be found at [embeddedcontainers/zephyr](https://github.com/embeddedcontainers/zephyr). Images are hosted on the GitHub Container Registry (GHCR) and can be found [here](https://github.com/embeddedcontainers/zephyr/pkgs/container/zephyr/versions?filters%5Bversion_type%5D=tagged). Examples are standalone repos with names that begin with `examples-zephyr-`. See all of the current examples [here](https://github.com/orgs/embeddedcontainers/repositories?q=examples-zephyr-&type=all&language=&sort=).

## nRF Connect SDK (NCS)

The [nRF Connect SDK](https://www.nordicsemi.com/Products/Development-software/nrf-connect-sdk) from Nordic Semiconductor is their unified SDK for their SoCs. It is based on Zephyr but includes additional functionality for their platform.

The main project can be found at [embeddedcontainers/ncs](https://github.com/embeddedcontainers/ncs). Images are hosted on the GitHub Container Registry (GHCR) and can be found [here](https://github.com/embeddedcontainers/ncs/pkgs/container/ncs/versions?filters%5Bversion_type%5D=tagged). Examples are standalone repos with names that begin with `examples-ncs-`. See all of the current examples [here](https://github.com/orgs/embeddedcontainers/repositories?q=examples-ncs-&type=all&language=&sort=).
