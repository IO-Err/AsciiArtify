| NAME | PROMPT | DESCRIPTION | EXAMPLE |
| -------- | -------- | -------- | -------- |
| pod | create pod resource | simple pod  | <a href="yaml/pod.yaml" target="_blank">pod.yaml</a> |
| livenessProbe | create pod with livenessprobe, path /healthz, period 5 | pod with sample livenessProbe | <a href="yaml/liveness.yaml" target="_blank">liveness.yaml</a> |
| readinessProbe | create pod with readinessProbe, path /healthr, period 5 | pod with sample readinessProbe | <a href="yaml/readness.yaml" target="_blank">readness.yaml</a> |
| volumeMounts | create pod with volumeMounts | pod with sample volumeMounts | <a href="yaml/volumeMounts.yaml" target="_blank">volumeMounts.yaml</a> |
| cronjob | create cronjob for two jobs, first one should be started everyday at 02:00 and second one should be started every friday at 04:00 | sample cronjob | <a href="yaml/cronjob.yaml" target="_blank">cronjob.yaml</a> |
| job | create sample job with init container | sample job | <a href="yaml/job.yaml" target="_blank">job.yaml</a> |
| multicontainer | create sample pod with 2 containers and one init container | sample pod with several containers | <a href="yaml/multicontainer.yaml" target="_blank">multcontainer.yaml</a> |
| resources | create pod with resources (requsts and limits) | sample pod with resources definition | <a href="yaml/resources.yaml" target="_blank">resources.yaml</a> |
| secret-env | create pod with env TOKEN exported from secret | sample pod with secret-env | <a href="yaml/secret-env.yaml" target="_blank">secret-env.yaml</a> |