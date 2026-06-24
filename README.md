# OpenShift Demos

## Intro

The repo contains some examples that should be runnable on any __OpenShift__ 4.x Cluster.

A default __StorageClass__ is necessary for some of the examples.

All resources can be created using ```oc apply -f .```. Exception: The  __kustomize__ example needs ```oc apply -k .```.

See the READMEs in the sub directories for further explanation.

## Testing

All the examples contain a __Service__ and a __Route__ to access the webserver.
