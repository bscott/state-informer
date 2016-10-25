![alt text](https://cdn.meme.am/instances/500x/66971439.jpg)


## Overview
Monitors Remote State in S3, Notifies team in Slack including a diff of the change!

## Install
Deployed as a Docker container ( bscott/state-informer). Just need to set a few environment
variables for Slack integration and S3 IAM credentials for reading of the state file that you wish to watch for changes.

## TODO
* Plan on adding other ways of notifications via email, Hipchat, etc .
* Plan on support other remote state providers like consul, etc.


#### Reference
* [State Interface](https://github.com/hashicorp/terraform/tree/master/state)
* [Listen for S3 Bucket Changes](https://docs.minio.io/docs/golang-client-api-reference#ListenBucketNotification)
