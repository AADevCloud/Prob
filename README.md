# Prob
Deploy all the manifest files
- Note: Development Pod will start and serving user immediately while prod pod take a time to start and server the user. So by this way you can test your reaidness prob test
- In  order to Test the liveness prob. first you need to interput the pod by following command
``` bash
<node-ip>:<nodeport>/freeze
#assume
172.18.0.30080/freeze
```

- if there is some internally problem in your application. readiness prob will restart the container unitll your pod become healty
