# Examples of yaml-manifests generated via kubectl-ai plugin
| NAME | PROMPT | DESCRIPTION | EXAMPLE |
| --- | --- | --- | --- |
| App | `kubectl kubectl-ai "create a pod for a basic application"` | Базовий маніфест для розгортання застосуну | [app.yaml](yaml/app.yaml) |
| Liveness Probe | `kubectl kubectl-ai "check if a container is alive”` | Перевірка, чи працює контейнер | [app-livenessProbe.yaml](yaml/app-livenessProbe.yaml) |
| Readiner Probe | `kubectl kubectl-ai "check if a container is ready”` | Перевірка, чи готовий контейнер до трафіку | [app-readinessProbe.yaml](yaml/app-readinessProbe.yaml) |
| Volume Mounts | `kubectl kubectl-ai "mount a volume”` | Підключення тома до контейнера для зберігання даних | [app-volumeMounts.yaml](yaml/app-volumeMounts.yaml) |
| CronJob | `kubectl kubectl-ai "CronJob”` | Створення завдання, яке буде виконуватись за роскладом | [app-cronjob.yaml](yaml/app-cronjob.yaml) |
| Job | `kubectl kubectl-ai "Job”` | Створення завдання, яке виконається одноразово | [app-job.yaml](yaml/app-job.yaml) |
| Multicontainer | `kubectl kubectl-ai "multicontainer pod”` | Створення мультиконтейнерного поду | [app-multicontainer.yaml](yaml/app-multicontainer.yaml) |
| Recources | `kubectl kubectl-ai "Set resource limits”` | Встановлення обмежеень ресуурсів | [app-resources.yaml](yaml/app-resources.yaml) |
| Secret Env | `kubectl kubectl-ai "define secret envs”` | Визначає змінні середовища для безпечної передачі чутливих данних | [app-secret-env.yaml](yaml/app-secret-env.yaml) |