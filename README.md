## Deploy to openshift using Docker strategy 

As the source code is equipped with ``Dockerfile`` definition, we can use docker deployment strategy to deploy the app.

```bash
$ oc new-app https://github.com/zeldi/welcome-node.git --name welcome
```
