# 20. The gcloud reference
  The gcloud CLI manages authentication and local configuration, as well as your interaction with the Google Cloud Platform APIs.

- Authenticate in gcloud (sign-in to Google Cloud Account). Inside the SSH session, run:
  ```
  gcloud auth login
  ```
- Check your current gcloud configuration. Inside the SSH session run:
  ```
  gcloud config list
  ```
## Identity and Access Management (IAM)
- View all the roles, run the following inside the SSH session run:
  ```
  gcloud iam roles list | grep "name:"
  ```
- 
## Google Compute Engine (GCE)
- To view your default region and zone
  ```
  gcloud config get-value compute/region
  ```
  ```
  gcloud config get-value compute/zone  
  ```
- You can view a list of regions and zones by running the following commands:
```
gcloud compute regions list
```
```
gcloud compute zones list
```
Set default region and zone in the metadata server:
```
gcloud compute project-info add-metadata --metadata google-compute-default-region=REGION,google-compute-default-zone=ZONE
```
Initialize the change in your local client:
```
gcloud init
```
Set default region and zone in your local client
```
gcloud config set compute/region REGION
```
```
gcloud config set compute/zone ZONE
```
- [Creating VMs](https://cloud.google.com/compute/docs/gcloud-compute/common-commands#working_with_vms)
  ```
  gcloud compute instances create VM_NAME \
    [--image IMAGE | --image-family IMAGE_FAMILY] \
    --image-project IMAGE_PROJECT
  ```
- [Listing VMs](https://cloud.google.com/compute/docs/gcloud-compute/common-commands#listing_vms)  
  ```
  gcloud compute instances list
  ```
- [Describing VMs](https://cloud.google.com/compute/docs/gcloud-compute/common-commands#describing_vms)
  ```
  gcloud compute instances describe VM_NAME
  ```
- [Starting VMs](https://cloud.google.com/compute/docs/gcloud-compute/common-commands#starting_vms)
  ```
  gcloud compute instances start VM_NAME
  ```
- [Stopping VMs](https://cloud.google.com/compute/docs/gcloud-compute/common-commands#stopping_vms)
  ```
  gcloud compute instances stop VM_NAME
  ```
## Google Kubernetes Engine (GKE)
   ```
   $ gcloud init --console-only # to setup default configuration
   $ gcloud config configurations create novatecConfig # creating custom config
   $ gcloud config configurations list
   $ gcloud info
   ```
   ``` 
   # Listing gcloud components 
   $ gcloud components list

   # if kubectl not available
   $ gcloud components install kubectl 

   $ gcloud components update                   # if required
   ```
   ```
    # Create a cloud cluster
    $ gcloud container clusters create zeus --machine-type n1-standard-2 --num-nodes 2 --zone us-central1-c
    # Verify K8s GKE Cluster details
    $ gcloud container clusters list
   ```
   ```
   Switch to cluster novatec 
   $ gcloud container clusters get-credentials novatec --zone us-central1-c --project novatec-python-app
   ```
## Google App Engine
  
## Google Persistent Disk

## Google Cloud Storage

## Virtual Private Cloud (VPC)

## Big Query

## API and Services




