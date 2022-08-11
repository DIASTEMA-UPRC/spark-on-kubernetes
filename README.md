# Spark on Kubernetes Installation
## Description
DIASTEMA is using Kubernetes to be able to handle a dynamic computing cluster for the workflows of its users [[1]](https://github.com/DIASTEMA-UPRC/openstack-heat-installation/blob/main/openstack-heat/heat-apis/use-heat-apis.md#references). With Kubernetes the Spark framework is getting used to scale workflows that are executing various algorithms of data analytics (like machine learning and neural networks) [[2]](https://github.com/DIASTEMA-UPRC/openstack-heat-installation/blob/main/openstack-heat/heat-apis/use-heat-apis.md#references).

Currently Spark and Kuberentes do not have versions that are compatible, but there are some  workarounds that give the ability to use Spark on a Kuberentes Cluster [[3]](https://github.com/DIASTEMA-UPRC/openstack-heat-installation/blob/main/openstack-heat/heat-apis/use-heat-apis.md#references).

In this repository, a documentation is given regarding the way in which Spark is installed on Kubernetes in the environment of the platform DIASTEMA [[4]](https://github.com/DIASTEMA-UPRC/openstack-heat-installation/blob/main/openstack-heat/heat-apis/use-heat-apis.md#references).

## Repository Contents
- spark-on-kubernetes
  - An MD documentation on how to install and use Spark on a Kubernetes Environment able to scale the Spark Workflows.

## References
- [1] https://kubernetes.io/
- [2] https://spark.apache.org/
- [2] https://spark.apache.org/docs/latest/running-on-kubernetes.html
- [3] https://diastema.gr/
