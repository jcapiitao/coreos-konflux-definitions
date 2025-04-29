# Konflux experimentation

## Prerequisites
  - Give repo access to [Konflux Fedora](https://github.com/apps/konflux-fedora)
  - [Get Konflux Fedora token for authentication](https://oauth-openshift.apps.kfluxfedorap01.toli.p1.openshiftapps.com/oauth/token/request)

## Deployment
```
oc apply -k fcos-pipeline-rawhide-jcapitao-kustomization/
oc apply -k cosa-jcapitao-kustomozation/
```
