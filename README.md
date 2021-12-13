# gcloud
Google Cloud tips

## Download CLI
https://cloud.google.com/sdk/gcloud


If terminal cannot open the brower, manually execute:
```
$ curl https://sdk.cloud.google.com | bash
$ gcloud auth login
```

# List zones
```
$ gcloud compute zones list
```

# Set zones
```
$ gcloud config set compute/region europe-west1
$ gcloud config set compute/zone europe-west1-c
$ gcloud config list --all
```

# Create Instance
```
$ gcloud compute instances create myinstance \
           --machine-type n1-standard-1 \
           --image ubuntu-19-00
```


# ssh
```
$ gcloud compute ssh myinstance
```

# list images
```
$ gcloud compute images list
```


