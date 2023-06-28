## Yolo Kubernetes Orchestration

### Description

This project uses K8 to orchestrate the Yolo app on a cluster and expose the app.

### Set up instructions

Ensure that you have Minikube installed on your machine.

Clone the repository.

Start Minikube on your machine

Then CD into the client and backend DIR and create the deployment, service, config, and PVC YAML files

Access the link shared on the deployment tab on your UI. Or you can get services from your terminal to access the external IP

### Known Bugs

The client-server image keeps failing upon restart (CrashLoop Error) (This is a bug from how the application was developed locally, the app keeps restarting)

### Technology used

- YAML

### License MIT License: Copyright (c) 2023
