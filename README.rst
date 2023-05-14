================================
example_docker_sybase_ase_python
================================

Examples for deploy Sybase ASE database with Docker and query
his data with Python.

Install
=======

Pre requirements for deploy with Docker, executing the following command:

::

    $ sudo apt update && sudo apt upgrade
    $ sudo apt install build-essential libpq-dev python3-dev
    $ pip install -U pip

Define some values for the deploy into the ``.env`` file, executing the
following command:

::

    $ cd example_docker_sybase_ase_python/
    $ cp .env.example .env
    $ nano .env

For deploy this software stack, you require the following software:

- `Docker Engine <https://docs.docker.com/engine/>`_.

    - `Docker Engine on Debian <https://docs.docker.com/engine/install/debian/>`_.

    - `Docker Engine on Ubuntu <https://docs.docker.com/engine/install/ubuntu/>`_.

- `Docker Compose <https://docs.docker.com/compose/>`_.


Use it
======

For run this stack docker containers, executing the following command:

::

    $ sudo docker compose up &

For stop this stack docker containers, executing the following command:

::

    $ sudo docker compose stop
