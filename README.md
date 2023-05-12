# README

## Installation

1. Install microk8s
1. Install istio operator
1. Install flux


## GKE Configuration

### Connect to a cluster

```sh
gcloud container clusters get-credentials growd --zone australia-southeast1-c --project growd-production
```

## Work in Progress

### Routing based on jwt

* https://istio.io/latest/docs/tasks/traffic-management/request-routing/
* https://istio.io/latest/docs/tasks/security/authentication/jwt-route/
* https://istio.io/latest/docs/tasks/security/authentication/authn-policy/#require-a-valid-token

* https://raw.githubusercontent.com/istio/istio/release-1.14/samples/bookinfo/platform/kube/bookinfo.yaml
* https://raw.githubusercontent.com/istio/istio/release-1.14/samples/bookinfo/networking/virtual-service-reviews-test-v2.yaml
* https://raw.githubusercontent.com/istio/istio/release-1.14/samples/bookinfo/networking/virtual-service-all-v1.yaml
* https://raw.githubusercontent.com/istio/istio/release-1.14/samples/bookinfo/networking/destination-rule-all.yaml
* https://raw.githubusercontent.com/istio/istio/release-1.14/samples/bookinfo/networking/virtual-service-reviews-test-v2.yaml
