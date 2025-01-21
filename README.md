# assessment

1. Apply the Kubernetes manifests:
   kubectl apply -f kubernetes/namespace.yaml
   kubectl apply -f kubernetes/deployment.yaml
   kubectl apply -f kubernetes/service.yaml
   kubectl apply -f monitoring/prometheus-config.yaml
   kubectl apply -f monitoring/prometheus-deployment.yaml
   kubectl apply -f monitoring/prometheus-service.yaml

2.Access your web application:   
   kubectl get svc -n web

3.Access Prometheus:
   kubectl get svc -n monitoring

