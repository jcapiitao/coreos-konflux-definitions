# Konflux experimentation

## Prerequisites
  - Give repo access to [Konflux Fedora](https://github.com/apps/konflux-fedora)
  - [Get Konflux Fedora token for authentication](https://oauth-openshift.apps.kfluxfedorap01.toli.p1.openshiftapps.com/oauth/token/request)

## Component cosa
```
oc apply -f application_fcos.yaml -f component_coreos-assembler.yaml
```
