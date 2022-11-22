# Prometheus+Grafana+AlertManager

git clone https://github.com/WANNA959/kube-prometheus
cd kube-prometheus
kubectl create -f ./setup
# 
kubectl create -f ./manifests
# network policy
kubectl create -f ./network-policy
# ding talk alert
kubectl create -f ./ding-talk