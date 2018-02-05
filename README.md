Blockchain Demo on OpenShift
====


Setup
----
To deploy Parity on OpenShift, use the provided template:

```
$ oc new-app -f parity-template.yaml
```

You can specify the version of Parity container image (default is `stable`) using template parameters:

```
$ oc new-app -f parity-template.yaml --param=PARITY_VERSION=v1.9.2
```