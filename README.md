# useR!2019 tutorial on Docker for Data Science

## Contents

See abstract on the [useR!2019 website](http://user2019.r-project.org/tutorials/#docker)

## Preparation for the tutorial

**It is absolutely mandatory to install the required software prior to the tutorial.**

### Software to install

By all means:

- [Docker](https://docs.docker.com/install/)
- [Docker Compose](https://docs.docker.com/compose/install/)

Optionally:

- [Kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/)
- [Minikube](https://kubernetes.io/docs/tasks/tools/install-minikube/)

**Note**: The Docker daemon needs to be configured to accept connections over
TCP, see https://www.shinyproxy.io/getting-started/#docker-startup-options
This will be explained in the tutorial, but it does not harm to already
configure it.

### Docker images to pull

```
docker pull hello-world
docker pull openanalytics/r-base
docker pull openanalytics/shinyproxy
docker pull openanalytics/shinyproxy-snapshot
docker pull openanalytics/shinyproxy-demo
docker pull openanalytics/shinyproxy-dash-demo
docker pull openanalytics/shinyproxy-rstudio-ide-demo
docker pull openanalytics/scheduled-reporting-demo
docker pull openanalytics/scheduled-reporting-demo-report
docker pull openanalytics/rdepot-repo
docker pull openanalytics/rdepot-app
docker pull openanalytics/rtq-client
docker pull redis
docker pull apache/zeppelin:0.8.1
```
## Git repositories to clone

- https://github.com/openanalytics/r-base
- https://github.com/openanalytics/shinyproxy-template
- https://github.com/openanalytics/shinyproxy-demo
- https://github.com/openanalytics/shinyproxy-config-examples
- https://github.com/openanalytics/shinyproxy-dash-demo
- https://github.com/openanalytics/shinyproxy-zeppelin-notebook-demo
- https://github.com/openanalytics/shinyproxy-rstudio-ide-demo
- https://github.com/openanalytics/scheduled-reporting-demo
- https://github.com/openanalytics/rdepot-demo
- https://github.com/openanalytics/rtq-docker


**See you in Toulouse!**
