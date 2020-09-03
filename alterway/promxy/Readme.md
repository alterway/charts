# Promxy

Promxy is a prometheus proxy that makes many shards of prometheus appear as a single API endpoint to the user

## Usage 

    $ helm install promxy alterway/promxy

## Requirement

* Helm 3

## Docker image 

* alterway/promxy

This chart use Alter Way's Promxy Docker image available publicly on the [Dockerhub](https://hub.docker.com/repository/docker/alterway/promxy).
Source are available in this [Git repo](https://github.com/alterway/promxy).

## Setup 

### Installing the Chart

    $ helm repod add alterway ....
    $ helm install promxy alterway/promxy

### Chart customization

Edit values.yaml then install the chart : 

    $ helm install promxy alterway/promxy -f values.yaml

### Uninstalling the Chart

    $ helm uninstall promxy


The command removes all the Kubernetes components associated with the chart and deletes the release.


