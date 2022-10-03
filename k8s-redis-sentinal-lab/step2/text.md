
Deploy Redis

`helm3 install redis -f /home/ubuntu/values.yaml bitnami/redis`

Deploy an app that talks to Redis

`kubectl create -f app.yaml`

Open the app to add data

[click here]{{TRAFFIC_HOST1_30123}}