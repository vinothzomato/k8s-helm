# Helm Client

### Container Details
[![](https://images.microbadger.com/badges/image/vinothzomato/k8s-helm.svg)](http://microbadger.com/images/vinothzomato/k8s-helm "Get your own image badge on microbadger.com")
[![](https://images.microbadger.com/badges/version/vinothzomato/k8s-helm.svg)](http://microbadger.com/images/vinothzomato/k8s-helm "Get your own version badge on microbadger.com")
[![](https://images.microbadger.com/badges/commit/vinothzomato/k8s-helm.svg)](http://microbadger.com/images/vinothzomato/k8s-helm "Get your own commit badge on microbadger.com")

# Supported tags and respective `Dockerfile` links
* `latest`    [(latest/Dockerfile)](https://github.com/vinothzomato/k8s-helm/blob/latest/Dockerfile)

## Overview
This container provides the Helm client for use with Kubernetes

## Run with tunneling
`kubectl run -it helm --env=HELM_HOST=<HOST>:<PORT> --image=vinothzomato/k8s-helm --command /bin/sh -n kube-system --rm=true` 

## Run without tunneling
`kubectl run -it helm --image=vinothzomato/k8s-helm --command /bin/sh -n kube-system --rm=true`


