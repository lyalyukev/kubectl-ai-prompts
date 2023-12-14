| NAME                   | PROMPT                   | DESCRIPTION                            | EXAMPLE                                                                                                   |
|------------------------|--------------------------|----------------------------------------|-----------------------------------------------------------------------------------------------------------|
| Deployment               | create an nginx deployment with 3 replicas  | Main configuration for the application | [app.yaml](https://github.com/lyalyukev/kubectl-ai-prompts/blob/main/yaml/app.yaml)                       |
| app-livenessProbe.yaml | create liveness probe for nginx container in deployment | Config for the liveness probe          | [app-livenessProbe.yaml](https://github.com/lyalyukev/kubectl-ai-prompts/blob/main/yaml/app-livenessProbe.yaml)   |
| app-readinessProbe.yaml| create readiness probe for nginx container in deployment  | Config for the readiness probe         | [app-readinessProbe.yaml](https://github.com/lyalyukev/kubectl-ai-prompts/blob/main/yaml/app-readinessProbe.yaml) |
| app-volumeMounts.yaml  | create nginx deployment with volumeMounts  | Configurations for volume mounts       | [app-volumeMounts.yaml](https://github.com/lyalyukev/kubectl-ai-prompts/blob/main/yaml/app-volumeMounts.yaml)     |
| app-cronjob.yaml       | create cronJob every one hour | Configuration for cron job              | [app-cronjob.yaml](https://github.com/lyalyukev/kubectl-ai-prompts/blob/main/yaml/app-cronjob.yaml)               |
| app-job.yaml           | create job that hit php file  | Configuration for job                   | [app-job.yaml](https://github.com/lyalyukev/kubectl-ai-prompts/blob/main/yaml/app-job.yaml)                       |
| app-multicontainer.yaml| create pod with php-fpm and nginx| Configuration for multi-container setup | [app-multicontainer.yaml](https://github.com/lyalyukev/kubectl-ai-prompts/blob/main/yaml/app-multicontainer.yaml) |
| app-resources.yaml     | create nginx deployment with resources allocation  | Configuration for resource allocation   | [app-resources.yaml](https://github.com/lyalyukev/kubectl-ai-prompts/blob/main/yaml/app-resources.yaml)           |
| app-secret-env.yaml    | create secret for nginx config  | Configuration for secret environment variables | [app-secret-env.yaml](https://github.com/lyalyukev/kubectl-ai-prompts/blob/main/yaml/app-secret-env.yaml)         |
