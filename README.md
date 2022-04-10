# Helm chart for Hello nginx project

Usage: 

`helm install chart_name ./`

To enable ingress:

`helm install chart_name ./ --set ingress.enabled=true`

To enable pod scaling: 

`helm install chart_name ./ --set autoscaling.enabled=true`