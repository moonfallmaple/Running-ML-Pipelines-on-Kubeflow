- Running-ML-Pipelines-on-Kubeflow
- Open the Cloud Shell and enter the following command to create the required GKE cluster:
```
gcloud container clusters create cluster-1 --zone us-central1-a --cluster-version 1.18.20 --machine-type n1-standard-2 --enable-basic-auth --scopes=https://www.googleapis.com/auth/cloud-platform
```
