#Path - inside helm-base-chart
helm package .\helm-chart\


helm upgrade --install sample ./Helm/helm-chart-one/ -f Helm/helm-chart-one/values.yaml -n testing