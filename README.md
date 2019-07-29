# Kubernetes ZooKeeper K8SZK

copy from retired [kubernetis/contrib statefulset zookeeper](https://github.com/kubernetes-retired/contrib/tree/master/statefulsets/zookeeper)
with updated zookeeper version `3.4.10` -> `3.4.14`

used to build a replacement image for `gcr.io/google_samples/k8szk:v3`

Differences from google samples image:

* fixed [autopurge bug](https://github.com/kubernetes-retired/contrib/commit/584b78cfcb88a9e432ee22701fb22b51face8d0d)
* [updated zookeeper patch level](c34458b)



Please refer to the [README_ORIGINAL.md]() for more details.
