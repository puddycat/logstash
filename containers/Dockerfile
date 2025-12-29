#
# logstash/containers/Dockerfile
#
# raymondstrose@hotmail.com
#
#   Create a Logstash Docker image.
#
#   docker build -f Dockerfile  \
#       --build-arg BASE_IMAGE="logstash" \
#       --build-arg BASE_IMAGE_TAG="8.19.5" \
#       --build-arg LOGSTASH_VERSION="8.19.5" \
#       -t raymondstrose/postgres:8.19.5 .
#

ARG	BASE_IMAGE="logstash"
ARG	BASE_IMAGE_TAG="8.19.5"
ARG	LOGSTASH_VERSION="8.19.5"

FROM $BASE_IMAGE:$BASE_IMAGE_TAG
LABEL MAINTAINER=raymondstrose@hotmail.com
