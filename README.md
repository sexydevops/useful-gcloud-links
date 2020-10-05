## Useful Google Cloud links

Resource manager: 
```
https://console.developers.google.com/cloud-resource-manager?folder=&organizationId=0
```

## Useful Google Cloud commands

### Create free VM for testing

```
gcloud compute instances create myproxy --machine-type=f1-micro --zone=us-west1-b --image=ubuntu-minimal-1804-bionic-v20200923 --image-project ubuntu-os-cloud
```

### Create a VM:

```
gcloud compute instances create instance-1 --machine-type=n1-standard-1 --zone=us-central1-b --preemptible --no-restart-on-failure --maintenance-policy=terminate
```
