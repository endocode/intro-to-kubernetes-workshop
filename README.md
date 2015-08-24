# Intro to Kubernetes Workshop

Kubernetes Version: 1.0.3

The slides from this workshop are hosted [online](http://go-talks.appspot.com/github.com/kelseyhightower/intro-to-kubernetes-workshop/slides/talk.slide#1)

## Course Outline

### Vagrant

#### Labs

  * [Install Vagrant](labs/install-vagrant.md)

### Kubernetes base infrastructure

#### Labs

  * [Provision CoreOS Cluster](labs/provisioning-coreos-on-vagrant.md)
  * [Install and configure Docker](labs/install-and-configure-docker.md)
  * [Configure Networking](labs/configure-networking.md)

### PKI infrastructure

#### Labs

  * [Initialize a certificate authority](labs/initialize-a-certificate-authority.md)
  * [Generate server and client certs](labs/generate-server-and-client-certs.md)

### Provision the Controller Node

#### Labs

  * [Install and configure the Kubernetes controller](labs/kuberentes-controller-pod.md)

### Provision the Kubernetes clients

#### Labs

  * [Install and configure the kubectl CLI](labs/install-and-configure-kubectl.md)
  * [Deploy the Web UI](labs/cluster-add-on-ui.md)

### Provision the Worker Nodes

#### Labs

  * [Install and configure the kubelet](labs/install-and-configure-kubelet.md)
  * [Install and configure the kube-proxy](labs/install-and-configure-kube-proxy.md)

### Managing Applications with Kubernetes

#### Labs

  * [Creating and managing pods](labs/pods.md)
  * [Creating and managing replication controllers](labs/replication-controllers.md)
  * [Creating and managing services](labs/services.md)
  * [Exposing services with nginx](labs/exposing-services-with-nginx.md)
  * [Rolling updates](labs/rolling-updates.md)

### Cluster Add-ons

#### Labs

  * [DNS](labs/cluster-add-on-dns.md)

## Links

  * [Kubernetes](http://googlecloudplatform.github.io/kubernetes)
  * [gcloud Tool Guide](https://cloud.google.com/sdk/gcloud)
  * [Docker](https://docs.docker.com)
  * [CoreOS](https://coreos.com)
  * [etcd](https://coreos.com/docs/distributed-configuration/getting-started-with-etcd)
  * [nginx](http://nginx.org)

### Tips

#### Destroy and delete Vagrant instances:

```
cd vagrant && vagrant destroy
```

#### Clean-up kubectl config file:

```
rm -rf ~/.kube
```
