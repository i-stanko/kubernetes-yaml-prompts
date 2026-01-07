# Kubernetes YAML Prompts Portfolio

This repository contains a portfolio of Kubernetes YAML manifests generated and documented using prompt engineering techniques.

## Manifests Overview

| NAME | PROMPT | DESCRIPTION | EXAMPLE |
| --- | --- | --- | --- |
| `app.yaml` | [Generate a basic Kubernetes Deployment](./prompts/app.prompt.md) | Base Kubernetes application manifest | [YAML](./yaml/app.yaml) |
| `app-livenessProbe.yaml` | [Add liveness probe to a Deployment](./prompts/app-livenessProbe.prompt.md) | Liveness probe configuration for containers | [YAML](./yaml/app-livenessProbe.yaml) |
| `app-readinessProbe.yaml` | [Add readiness probe to a Deployment](./prompts/app-readinessProbe.prompt.md) | Readiness probe configuration | [YAML](./yaml/app-readinessProbe.yaml) |
| `app-volumeMounts.yaml` | [Add volume mounts to a Pod](./prompts/app-volumeMounts.prompt.md) | Volume mounts and persistent storage | [YAML](./yaml/app-volumeMounts.yaml) |
| `app-cronjob.yaml` | [Create a Kubernetes CronJob](./prompts/app-cronjob.prompt.md) | Scheduled job using Kubernetes CronJob | [YAML](./yaml/app-cronjob.yaml) |
| `app-job.yaml` | [Create a Kubernetes Job](./prompts/app-job.prompt.md) | One-time execution Job manifest | [YAML](./yaml/app-job.yaml) |
| `app-multicontainer.yaml` | [Create a multi-container Pod](./prompts/app-multicontainer.prompt.md) | Multi-container Pod example | [YAML](./yaml/app-multicontainer.yaml) |
| `app-resources.yaml` | [Define resource requests and limits](./prompts/app-resources.prompt.md) | CPU and memory requests/limits | [YAML](./yaml/app-resources.yaml) |
| `app-secret-env.yaml` | [Inject secrets as environment variables](./prompts/app-secret-env.prompt.md) | Environment variables sourced from Secrets | [YAML](./yaml/app-secret-env.yaml) |
