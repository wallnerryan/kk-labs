
Deploy Redis

`helm install redis -f values.yaml bitnami/redis`

Wait until all Redis pods are running 2/2

`kubectl get po`

Deploy an app that talks to Redis

`kubectl create -f app.yaml`

Open the app to add data

[click here]({{TRAFFIC_HOST1_30123}})