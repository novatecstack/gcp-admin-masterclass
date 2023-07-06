# 20. The gcloud reference
  The gcloud CLI manages authentication and local configuration, as well as your interaction with the Google Cloud Platform APIs.


## Identity and Access Management (IAM)
  
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
- Starting VMs
  ```
  gcloud compute instances start VM_NAME
  ```
- [Stopping VMs](https://cloud.google.com/compute/docs/gcloud-compute/common-commands#stopping_vms)
  
## Google Kubernetes Engine (GKE)
  
## Google App Engine
  
## Google Persistent Disk

## Google Cloud Storage

## Virtual Private Cloud (VPC)

## Big Query

## API and Services




