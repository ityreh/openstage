# OpenStage

OpenStage is an Open Source Developer Portal

## Helm

You can verify Helm-Charts by linting and generating to check:

    helm lint ./helm
    helm template helm-test-release ./helm

Install on K8s cluster:

    helm upgrade --install openstage-dev ./helm -f ./helm/environments/values-dev.yaml
