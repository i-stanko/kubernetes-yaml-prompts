Generate a Kubernetes Deployment manifest that demonstrates the use of a liveness probe.

Requirements:
- Use apiVersion apps/v1
- Kind: Deployment
- Application name: my-app
- Single container running image my-app:1.0.0
- Expose container port 8080
- Configure an HTTP liveness probe
- Liveness probe should check path /health on port 8080
- initialDelaySeconds: 15
- timeoutSeconds: 2
- Use consistent labels and selectors
- Keep the manifest clean and minimal

The output should focus on liveness probe configuration only.
