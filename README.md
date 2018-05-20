# web-nodejs

`oc new-app nodejs~https://github.com/bugbiteme/web-nodejs.git --name=web`

`oc logs -f bc/web`

`oc expose svc/web`

`oc get route web`

`Point browser to route`