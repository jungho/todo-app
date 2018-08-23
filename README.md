# Todo List Microservice Application #

The Todo application is a simple microservice based application comprised of a ReactJS UI, a node Users API and a Java TodoItem API.  For a database, mongodb is leveraged.  We will use this application to demonstrated CI/CD approaches for Kubernetes and Openshift.

![Todo app architecture](./todo-app.png)

## Manually Deploy the application ##

This is a good exercise to understand what is required to manually deploy a micro-service based application to Kubernetes. See [manual-k8s-deploy/README.md](https://github.com/jungho/k8s-bootcamp/blob/master/todo-app/manual-k8s-deploy/README.md)

## Deploy the application using Helm ##

As your applications become more complex, you will quickly realize that you will need Helm to package your applications.  See [helm/README.md](https://github.com/jungho/k8s-bootcamp/blob/master/helm/README.md)
