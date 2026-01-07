Generate a Kubernetes CronJob manifest.

Requirements:
- Use apiVersion batch/v1
- Kind: CronJob
- Name: my-app-cronjob
- Schedule the job to run every minute
- Use a container with image my-app:1.0.0
- Execute a shell command that prints the date and a message
- Set restartPolicy to OnFailure
- Include basic labels
- Follow modern Kubernetes best practices

The manifest should demonstrate a production-ready CronJob example.
