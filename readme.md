# pi4-monitoring

This is completely based on https://rpi4cluster.com/monitoring/monitor-intro/

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
