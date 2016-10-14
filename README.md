![Datasticks Logo](https://s3-us-west-2.amazonaws.com/advancedspark.com/img/datasticks-logo.png)

### The Lightweight, 100% Open Source Alternative for Streaming Analytics, ML, and AI

## Live Demo
* Click [here](http://datasticks.com) for a live, non-secure demo.  

**Note:  Do not load any sensitive data into this environment!**

## Related Projects
* Click [here](https://github.com/fluxcapacitor/pipeline) for a related project used for workshops

## Setup Kubernetes Cluster
* Follow the instructions [here](https://github.com/fluxcapacitor/kubernetes.ml#setup-a-new-kubernetes-cluster).

## Setup Kubernetes Client CLI
* Follow the instructions [here](https://github.com/fluxcapacitor/kubernetes.ml#install-kubernetes-client).

## Clone this Repo including Submodules
```
git clone --recursive https://github.com/fluxcapacitor/datasticks.com
```

## Deploy to Kubernetes Cluster
```
./datasticks-up.sh
```

## Get Apache2 Host/IP
```
kubectl get svc -w
```

## Navigate Browser to Apache2 Host/IP 
```
http://<apache2-host-ip>
```

## Support
* Email **help@fluxcapacitor.com** for Support!
