# HMCTS AzCopy Docker Image
---
Use this image to transfer files to/from Azure storage.

https://docs.microsoft.com/en-us/azure/storage/common/storage-use-azcopy-linux
---
## Building
This is an automated build on Dockerhub.  To build a new version, ensure that you tag the image and use the tagged version in your build:

    git tag 7.2.0-netcore-1.1
    git push --tags

The format of the tag is `azcopy version`-`Dockerfile version`.  Use the output of `azcopy --version` to determine the AzCopy version.  In the above example we have AzCopy version 7.2.0-netcore and version `1.1` of our Dockerfile.



