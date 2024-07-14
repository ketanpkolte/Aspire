# Deploy a cloud-native application automatically

The module shows you how to:

- Authenticate GitHub Actions to a container registry.
- Securely store sensitive information that GitHub Actions uses.
- Implement an action to build the container image for a microservice.
- Modify and commit the microservice code to trigger a build.
- Implement an action to deploy the updated container to an Azure Kubernetes Service (AKS) cluster.
- Modify and commit a Helm chart to trigger the deployment.
- Revert the microservice to the previous deployment.