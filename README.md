# Kubernetes YAML Prompts Portfolio

This repository contains a portfolio of Kubernetes YAML manifests generated and documented using prompt engineering techniques.

## Manifests Overview

| NAME | PROMPT | DESCRIPTION | EXAMPLE |
| --- | --- | --- | --- |
| `app.yaml` | [Prompt](./prompts/app.prompt.md) | Base Kubernetes application manifest | [YAML](./yaml/app.yaml) |
| `app-livenessProbe.yaml` | [Prompt](./prompts/app-livenessProbe.prompt.md) | Liveness probe configuration for containers | [YAML](./yaml/app-livenessProbe.yaml) |
| `app-readinessProbe.yaml` | [Prompt](./prompts/app-readinessProbe.prompt.md) | Readiness probe configuration | [YAML](./yaml/app-readinessProbe.yaml) |
| `app-volumeMounts.yaml` | [Prompt](./prompts/app-volumeMounts.prompt.md) | Volume mounts and persistent storage | [YAML](./yaml/app-volumeMounts.yaml) |
| `app-cronjob.yaml` | [Prompt](./prompts/app-cronjob.prompt.md) | Scheduled job using Kubernetes CronJob | [YAML](./yaml/app-cronjob.yaml) |
| `app-job.yaml` | [Prompt](./prompts/app-job.prompt.md) | One-time execution Job manifest | [YAML](./yaml/app-job.yaml) |
| `app-multicontainer.yaml` | [Prompt](./prompts/app-multicontainer.prompt.md) | Multi-container Pod example | [YAML](./yaml/app-multicontainer.yaml) |
| `app-resources.yaml` | [Prompt](./prompts/app-resources.prompt.md) | CPU and memory requests/limits | [YAML](./yaml/app-resources.yaml) |
| `app-secret-env.yaml` | [Prompt](./prompts/app-secret-env.prompt.md) | Environment variables sourced from Secrets | [YAML](./yaml/app-secret-env.yaml) |
