Generate a Kubernetes Job manifest for a run-to-completion task.

Requirements:
- Use apiVersion batch/v1
- Kind: Job
- Job name: my-app-job
- Use a single container with image my-app:1.0.0
- Run a simple shell command that prints the current date and a message
- Use args to execute the command
- Set restartPolicy to OnFailure
- Keep the manifest minimal and production-style

The manifest should demonstrate a basic Kubernetes Job use case.
