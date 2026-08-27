# grafana-v5
Install and instantiate Grafana v5 on Openshift, the simplest way

You must edit ClusterRoleBinding (crolebinding.yaml file) and set the namespace tag, the rest is fully automatic.

Works within Grafana 5.24.0... but some versions has problems with httpHeaderValue1: 'Bearer ${token}'
