# test_travis_minikube

This is a test repo to integrate trabis build using minikube to create an integration environment.

Main ideas taken from https://blog.travis-ci.com/2017-10-26-running-kubernetes-on-travis-ci-with-minikube

[![Build Status](https://travis-ci.org/aroundthecode/test_travis_minikube.svg?branch=master)](https://travis-ci.org/aroundthecode/test_travis_minikube)

Keep an eye on thread https://github.com/kubernetes/minikube/issues/2704 to get details on adjustments

* localkube bootstrap removed in minikbe v 0.29.0 
https://github.com/kubernetes/minikube/blob/v0.29.0/CHANGELOG.md
* most recent kubernetes version allowed is then 1.10.0
