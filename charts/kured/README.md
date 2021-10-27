# Helm chart: kured

[![CI-kured](https://github.com/wozorio/helm-charts/actions/workflows/ci-kured.yaml/badge.svg)](https://github.com/wozorio/helm-charts/actions/workflows/ci-kured.yaml)

This Helm chart deploys the official [kured](https://github.com/weaveworks/kured) chart as a dependency.

The advantage of this approach is that it allows me to further customize the deployment with additional templates if needed.

## Installation

1. Clone the repository
    ```
    git clone https://github.com/wozorio/helm-charts.git
    ```
1. Change to the repository directory
    ```
    cd helm-charts
    ```
1. Update the chart dependencies
    ```
    helm dependency update kured
    ```
1. Install the chart
    ```
    helm install kured ./kured
    ```
