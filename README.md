# Docker Alpine Hugo

Updated from [jonathanbp](https://github.com/jonathanbp/docker-alpine-hugo)'s docker-alpine-hugo image, with [anigeo](https://github.com/anigeo/docker-awscli/blob/master/Dockerfile)'s alpine awscli support.

This version includes SSH to aid in Bitbucket Pipelines and fetching Git Submodules.

Minimal (~130 MB) [Hugo](https://gohugo.io) Microcontainer with AWS CLI and git. Based off offical [Alpine](https://hub.docker.com/_/alpine/) 3.2 image.

## Usage

    docker run --rm freakingawesome/alpine-hugo-aws:latest
