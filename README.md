## Docker Base: Puppetmaster


This repository contains **Dockerbase** of [Puppetmaster](https://puppetlabs.com/) for [Docker](https://www.docker.com/)'s [Dockerbase build](https://registry.hub.docker.com/u/dockerbase/puppetmaster/) published on the public [Docker Hub Registry](https://registry.hub.docker.com/).


### Depends on:

* [dockerbase/service](https://registry.hub.docker.com/u/library/service/)


### Installation

1. Install [Docker](https://docs.docker.com/installation/).

2. Download [Dockerbase build](https://registry.hub.docker.com/u/dockerbase/puppetmaster/) from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull dockerbase/puppetmaster`


### Usage

    $ sudo docker run -it -p 8140:8140 --hostname puppetmaster --name dockerbase-puppetmaster --restart=always -d dockerbase/puppetmaster /sbin/runit
    $ sudo docker stop dockerbase-puppetmaster
    $ sudo docker start dockerbase-puppetmaster
    ...
    $ sudo docker rm dockerbase-puppetmaster

### Components & Versions

    Description:	Ubuntu 14.04.1 LTS
    git version 1.9.1
    OpenSSH_6.6.1p1 Ubuntu-2ubuntu2, OpenSSL 1.0.1f 6 Jan 2014
    puppet:3.7.4
