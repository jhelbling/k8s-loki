# k8s-loki
Helm less loki deployment.

kubectl create ns monitoring
kubectl apply -f loki
kubectl apply -f promtail

Add as data sources loki to your Grafana, e.g. http://loki.monitoring.svc:3100
