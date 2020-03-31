# boinc-docker

A very simple boinc docker configuration

## Installation

* Install docker
* Install docker-compose
* Create a `.env` file (use the `.env.example` as template but use a secure password)
* Start boinc (e.g. using the `build.sh`)


## Scripts

* **build.sh** : Just start a container using docker-compose (will be detached)
* **upgrade.sh** : Pull newest version from the `boinc/client` image and build
