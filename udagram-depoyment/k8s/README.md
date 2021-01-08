# Udagram Image Filtering Microservice

Udagram is a simple cloud application developed alongside the Udacity Cloud Engineering Nanodegree. It allows users to register and log into a web client, post photos to the feed, and process photos using an image filtering microservice.

## Tasks

### Setup Kubenetes
This assumes that you have minikube and kubectl installed. Open a new terminal within the project directory and run:

1. Apply configurations: `for i in $(ls *.yaml); do echo $i; kubectl apply -f $i; done;`
2. List all running pods: `kubectl get pods`