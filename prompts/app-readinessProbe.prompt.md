Generate a Kubernetes Deployment manifest that demonstrates the use of a readiness probe.

Requirements:
- Use apiVersion apps/v1
- Kind: Deployment
- Application name: my-app
- Single container running image my-app:1.0.0
- Expose container port 8080
- Configure an HTTP readiness probe
- Readiness probe should check path /ready on port 8080
- initialDelaySeconds: 5
- periodSeconds: 10
- Use consistent labels and selectors
- Keep the manifest clean and minimal

The output should focus on readiness probe configuration only.
