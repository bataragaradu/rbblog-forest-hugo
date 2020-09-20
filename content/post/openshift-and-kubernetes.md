+++
authors = []
date = 2020-09-28T21:00:00Z
draft = true
excerpt = "Lets see how kubernetes comes in picture in the openshift environment"
hero = "/images/openshift-preview.jpg"
timeToRead = 5
title = "Openshift and Kubernetes"

+++
OpenShift is a platform as a service (PaaS) from Red Hat that is built on Docker and Kubernetes. Kubernetes is an open source, container as a service (CaaS) project originating from Google

[![](https://lh4.googleusercontent.com/3XU6jvGyinbFikv18mjAsbO4rnK0SUZ6pwu3GUcVl95HGFVLufun1NFNAowXLFLBnJ9yusiU-YBK3fO7aoVQCHU8yg8KKY95qwYAQe8kGmfX1m5YMBk5KUKKUHnyuuUrjYTCqUvw =502x375)](https://miro.medium.com/max/502/0*n2dGPTi4tIlyo7Jf.png)

Request Routing:

An OpenShift Enterprise administrator can deploy routers to nodes in an OpenShift Enterprise cluster, which enable routes created by developers to be used by external clients

The route is an Openshift construct that defines the rules you want to apply to incoming connections.

This matches the[ Ingress](https://kubernetes.io/docs/user-guide/ingress/) and[ Ingress Controller](https://kubernetes.io/docs/user-guide/ingress/#ingress-controllers) resources in Kubernetes.

Where in Kubernetes the Ingress Controller could be a NGINX container providing reverse proxy capabilities, and the Ingress Resource defines the connection rules.

![](https://lh6.googleusercontent.com/goNSF45mmkcxV3qLtoAmLvam_K7nVReZa02c0LD-HlV123yIYPSZDWHpLL1bGx-qxk5a3-0R1Qxk_5UhT-hYrhOs8NkZ7Hszk8A-14ouw9lT7cpoG0q_RCBMrLyAbcqmbgoJXL4S =602x141)

## **Namespace**

“The primary grouping concept in Kubernetes is the namespace. Namespaces are also a way to divide cluster resources between multiple uses. That being said, there is no security between namespaces in Kubernetes; if you are a “user” in a Kubernetes cluster, you can see all the different namespaces and the resources defined in them.”

## **Project**

“The first new concept OpenShift adds is project, which effectively wraps a namespace, with access to the namespace being controlled via the project. Access is controlled through an authentication and authorization model based on users and groups. Projects in OpenShift therefore provide the walls between namespaces, ensuring that users, or applications, can only see and access what they are allowed to.”

Reference:

[https://medium.com/levvel-consulting/the-differences-between-kubernetes-and-openshift-ae778059a90e](https://medium.com/levvel-consulting/the-differences-between-kubernetes-and-openshift-ae778059a90e "https://medium.com/levvel-consulting/the-differences-between-kubernetes-and-openshift-ae778059a90e")