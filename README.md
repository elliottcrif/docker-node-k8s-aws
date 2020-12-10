# Docker-node-k8s-aws

[![Dockerhub badge](http://dockeri.co/image/elliottcrifasi/docker-node-k8s-aws)](https://hub.docker.com/r/elliottcrifasi/docker-node-k8s-aws)

Docker-powered build/deployment environment for Node.js projects on AWS. This Docker image is intended for use with [Bitbucket Pipelines](https://bitbucket.org/product/features/pipelines) and [AWS CodeBuild](https://aws.amazon.com/codebuild).

This image is based on node:14-alpine and has kubectl v1.2.0, the AWS CLI and Yarn installed (see Dockerfile for all other installed utilities).
