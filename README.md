# Golang Microservices, Kubernetes on Google Cloud Platform

## Create a GCE Account
https://console.cloud.google.com

## Create a Project
https://support.google.com/cloud/answer/6251787

## Enable *Compute Engine* and *Container Engine* APIs
https://developers.googleblog.com/2016/03/introducing-google-api-console.html

## Enable and explore Cloud Shell
https://cloud.google.com/shell/docs/
https://cloud.google.com/shell/docs/quickstart

## Configure Your Cloud Shell Environment
```
$ gcloud compute zones list
$ gcloud config set compute/zone us-central1-a
```

## Download the latest version of Go
```
$ wget https://storage.googleapis.com/golang/go1.7.5.linux-amd64.tar.gz
$ sudo rm -rf /usr/local/go
$ sudo tar -C /usr/local -xzf go1.7.5.linux-amd64.tar.gz
$ echo "export GOPATH=~/go" >> ~/.bashrc
$ source ~/.bashrc
```

## Get the Code
```
$ mkdir -p $GOPATH/src/github.com/bnannier
$ cd $GOPATH/src/github.com/bnannier
$ git clone https://github.com/bnannier/gokgcp
$ cd gokgcp/app
```
