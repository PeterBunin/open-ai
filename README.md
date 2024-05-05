# open-ai
open-ai k8s plugin demo

| Name | Prompt | Description   | Example   |
|---   |---     |---            |---        |
|app    | create deployment app with image demo-app:1.0.0 | Creates simple app with image app:1.0.0               |[app.yaml](/yaml/app.yaml)           |
|livnessProbe| create deployment app with image demo-app:1.0.0 | Creates simple app with default livenesprobe params|[app-livenessProbe.yaml](/yaml/app-livenessProbe.yaml)    |
|redinessProbe  |create pod app with image demo-app:1.0.0 and readinessProbe | Creates simple app with default redinessprobe params | [app-redinessProbe.yaml](/yaml/app-redinessProbe.yaml)|
|volumeMount| create pod app with image demo-app:1.0.0 and volumeMount | Creates simple app with default volumemount params | [app-volumeMounts.yaml](/yaml/app-volumeMounts.yaml)|
|cronJob| create pod app with image demo-app:1.0.0 and cronJob | Creates simple app with default cronjob params |[app-cronjob.yaml](/yaml/app-cronjob.yaml)|
|job| create pod app with image demo-app:1.0.0 and job | Creates simple app with default job params |[app-job.yaml](/yaml/app-job.yaml)|
|multicontainer| create pod app with image demo-app:1.0.0 and multicontainer |Creates simple app with two images as example|[app-multicantainer.yaml](/yaml/app-multicontainer.yaml)|
|resourses| create pod app with image demo-app:1.0.0 and resources |Creates simple app with default resources params as example| [app-resources.yaml](/yaml/app-resources.yaml)|
|secret-env| create pod app with image demo-app:1.0.0 and secret-env username and password | creates simple app with secret-env params (username and password)| [app-secret-env.yaml](/yaml/app-secret-env.yaml)|