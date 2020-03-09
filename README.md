# Build Engine
This image is intented to automate the build process that require npm, bower, gulp and pythonb.

The image includes the following software

  * python 2.7
  * nodejs 6
  * npm
  * bower
  * gulp
  * gcloud SDK
  * gcloud python Appengine SDK

The following library is installed:

  * libpng-dev

## running the container

```
docker run --rm abegodong/build-engine python -V
```
