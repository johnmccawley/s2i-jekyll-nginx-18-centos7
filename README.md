Jekyll Docker Images
====================

This repository contains the source for building static websites using
[Jekyll](https://jekyllrb.com/) that will be served with
[nginx 1.8](http://nginx.org/) for a reproducible Docker image using
[source-to-image](https://github.com/openshift/source-to-image).
The resulting image can be run using [Docker](http://docker.io) or preferably
hosted in Openshift and Kubernetes on Digital Garage.

For more information about using these images with Digital Garage, please see the
official [OpenShift Documentation](https://docs.thedigitalgarage.io/using_images/s2i_images/ruby.html).

Versions
---------------
Ruby versions currently provided are:
* ruby-2.2

nginx versions currently provided are:
* nginx-1.8

CentOS versions currently supported are:
* CentOS7
