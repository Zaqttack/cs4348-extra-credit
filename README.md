# cs4348-extra-credit

## Requirements

* utilize gcloud's GKE environemnts
* create a cluster with 3 nodes
* create a python docker image app
* be able to connect to my cluster from an external IP

## Included

### files

* app.py
* Dockerfile
* deployment.yaml
* service.yaml

### documentation

Learning these services separately really challegend me in a way to figure out how to combine them all together. These APIs and services needed to work in a way to, in the end, serve a link outside of the containerized pods!

Learning to combine these services was definitely a challenge. Needing to learn how to create a deployment.yaml to work with the services needed to make my python application exposed thru an external IP. These challeges were swayed once I also learned about Googles Artifact registery where I was able to create a docker image that was easibly accessible for kubernetes builds!

These services were able to work together with a single docker image and some .yaml files! You can actually see my "Hello World" in [action here](http://35.192.68.75/)! This is built by the short python script here in this repo and given guildeines to deploy the 3 required nodes for the kubernetes cluster. I then utilized the service.yaml to basically expose the pods ports. 

All in all, this extra credit was really fun to learn how to put together some of our labs from class. Would honestly recommend this being an assignment for the students in the future!
