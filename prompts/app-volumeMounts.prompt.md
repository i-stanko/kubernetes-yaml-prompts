Generate a Kubernetes Deployment manifest that demonstrates how to use volumes and volume mounts.

Requirements:
- Use apiVersion apps/v1
- Kind: Deployment
- Application name: my-app
- Single container using image my-app:1.0.0
- Expose container port 8080
- Define an emptyDir volume for ephemeral storage
- Mount the volume into the container at /app/data
- Use consistent labels and selectors
- Keep the manifest minimal and easy to understand

The manifest should illustrate basic volumeMount usage in Kubernetes.
