# Helm chart: hello-world

This Helm chart deploys the [tutum/hello-world](https://hub.docker.com/r/tutum/hello-world) app.

The purpose of this chart is to serve as reference for future developments.

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
    helm dependency update hello-world
    ```
1. Install the chart
    ```
    helm install hello-world ./hello-world
    ```
