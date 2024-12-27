controlplane $ k rollout history deployment video-app --revision=3
deployment.apps/video-app with revision #3
Pod Template:
  Labels:       app=video-app
        pod-template-hash=69648db755
  Containers:
   redis:
    Image:      redis:7.0.13
    Port:       <none>
    Host Port:  <none>
    Environment:        <none>
    Mounts:     <none>
  Volumes:      <none>
  Node-Selectors:       <none>
  Tolerations:  <none>

controlplane $ echo "3,redis:7.0.13" > app-file.txt
controlplane $ 
