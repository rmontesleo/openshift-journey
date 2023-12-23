# oc commands


## First hour.. Sander samples
```bash

oc whoami

oc get all

# You first create a project
oc new-project <PROYECT_NAME>

# You can add applications to this project with the new-app command
oc new-app rails-postgresql-example

# Use kubectl to deploy a simple K8s application
kubectl create deployment hello-node --image=resigry.k8s.io/e2e-test-images/agnhost:2.43 -- /agnhost serve-hostname

#
oc run testpod --image=nginx:1.23
kubectl get pods

#
oc run testpod --image=bitnami/nginx:1.23
oc get pods
oc delete pod testpod

#
oc run testpod --image=bitnami/nginx:1.23
oc get pods

#
oc run sleepytest --image=bitnami/busybox:1.27

#
oc get projects

```