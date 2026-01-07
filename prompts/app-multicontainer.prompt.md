Generate a Kubernetes multi-container Pod manifest.

Requirements:
- Use apiVersion v1
- Kind: Pod
- Name: my-app-multicontainer
- Demonstrate the sidecar pattern
- Main container runs an application on port 8080
- Sidecar container handles logging by reading shared files
- Use a shared emptyDir volume
- Add meaningful container names and labels
- Follow Kubernetes best practices

The manifest should clearly demonstrate a real-world multi-container Pod use case.
