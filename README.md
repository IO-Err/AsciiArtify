| NAME | PROMPT | DESCRIPTION | EXAMPLE |
| -------- | -------- | -------- | -------- |
| pod | create pod resource | simple pod  | <a href="yaml/app.yaml" target="_blank">app.yaml</a> |
| livenessProbe | create pod with livenessprobe, path /healthz, period 5 | pod with sample livenessProbe | <a href="yaml/app-livenessProbe.yaml" target="_blank">app-livenessProbe.yaml</a> |
| readinessProbe | create pod with readinessProbe, path /healthr, period 5 | pod with sample readinessProbe | <a href="yaml/app-readinessProbe.yaml" target="_blank">app-readinessProbe.yaml</a> |
| volumeMounts | create pod with volumeMounts | pod with sample volumeMounts | <a href="yaml/app-volumeMounts.yaml" target="_blank">app-volumeMounts.yaml</a> |
| cronjob | create cronjob for two jobs, first one should be started everyday at 02:00 and second one should be started every friday at 04:00 , k8s api version: batch/v1 | sample cronjob | <a href="yaml/app-cronjob.yaml" target="_blank">app-cronjob.yaml</a> |
| job | create sample job with init container | sample job | <a href="yaml/app-job.yaml" target="_blank">app-job.yaml</a> |
| multicontainer | create sample pod with 2 containers and one init container | sample pod with several containers | <a href="yaml/app-multicontainer.yaml" target="_blank">app-multcontainer.yaml</a> |
| resources | create pod with resources (requsts and limits) | sample pod with resources definition | <a href="yaml/app-resources.yaml" target="_blank">app-resources.yaml</a> |
| secret-env | create pod with env TOKEN exported from secret | sample pod with secret-env | <a href="yaml/app-secret-env.yaml" target="_blank">app-secret-env.yaml</a> |