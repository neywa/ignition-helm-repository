# ignition-openshift

This is a Helm Chart Repository for Ignition application on Red Hat OpenShift Container Platform 4.

The repository can be created from enclosed ignition-helm-repo.yaml file:

```# oc create -f ignition-helm-repo.yaml```

Run ```helm install --create-namespace ignition alpha/ignition/.``` to install
then manually start the build for the init container over the OpenShift GUI
