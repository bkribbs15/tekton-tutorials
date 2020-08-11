# Tekton Tutorials

Tekton tutorials is setup in order to be a starting block for building tekton pipelines.  There will be an array of tasks, taskruns, pipelines, and pipeline run examples for anyone to use and modify.

*** Current Compatiable Tekton Version: *** 15.0

## Tekton Installation 

Kubernetes 
```
kubectl apply --filename https://storage.googleapis.com/tekton-releases/pipeline/latest/release.yaml
```

OpenShift
```
kubectl apply --filename https://storage.googleapis.com/tekton-releases/pipeline/latest/release.notags.yaml
```

Dashboard (Optional)
```
kubectl apply --filename https://github.com/tektoncd/dashboard/releases/latest/download/tekton-dashboard-release.yaml
```