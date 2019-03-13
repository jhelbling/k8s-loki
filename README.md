# k8s-loki
Helm less loki deployment.

kubectl create ns monitoring
<br>
kubectl apply -f loki
<br>
kubectl apply -f promtail
<br>

Add as data sources loki to your Grafana, e.g. http://loki.monitoring.svc:3100
