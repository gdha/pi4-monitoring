# pi4-monitoring

This is completely based on https://rpi4cluster.com/monitoring/monitor-intro/

The purpose of this project is to introduce prometheus to gather some nice cluster metrics and grafana to be able to visualize the output from graphite in a nice graphs, like:

* The raw graphite celsius graph: 
<img alt="graphite browser" src="images/grahpite.png" width="400">

* The nices grafana celsius graph:
<img alt="grafana browser" src="images/pi4-celsius-grafana.png" width="400">

The sequence of execution is the following:

* prometheus-operator
  - cd prometheus-operator
  - cat readme (for the steps to be taken)
* node-exporter
  - cd node-exporter
  - cat readme (for the steps to be taken)
* kube-state-metrics
  - cd kube-state-metrics
  - cat readme (for the steps to be taken)
* kubelet
  - cd kubelet
  - cat readme (for the steps to be taken)
* traefik
  - cd traefik
  - cat readme (for the steps to be taken)
* prometheus
  - cd prometheus
  - cat readme (for the steps to be taken)
* add longhorn-servicemonitor
  - kubectl apply -f longhorn-servicemonitor.yaml
* grafana
  - cd grafana
  - cat readme (for the steps to be taken)
