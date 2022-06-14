# ignition-openshift

This is a Helm Chart Repository for Ignition application on Red Hat OpenShift Container Platform 4.

The repository can be created from enclosed ignition-helm-repo.yaml file:

```# oc create -f ignition-helm-repo.yaml```

To run the deployment create a namespace for ignition:

```# oc new-project ignition```

Then go to OpenShift UI and switch to the **Developer** perspective:

Helm > 'Install a Helm Chart from the developer catalog' > Filter for 'ignition' > Install Helm Chart

Make sure that you are installing the chart in the correct namespace.

There is also an option to run the installation without creating the repository. Just clone this git repository and un ```# helm install --create-namespace ignition alpha/ignition/.``` to install.
