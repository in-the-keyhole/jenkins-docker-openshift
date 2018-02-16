# Jenkins docker images repository

This repository contains jenkins docker images to run on openshift.
This has been tested on an Openshift cluster and this is based on official Openshift jenkins based image.

## Jenkins master

The jenkins master image is based on the official [openshift/jenkins](https://github.com/openshift/jenkins) image.
More information [here](2/README.md).

## Jenkins slave images

Here is the current list of images:

* [jenkins-slave-maven](slave-maven/README.md)
* [jenkins-slave-nodejs](slave-nodejs/README.md)
