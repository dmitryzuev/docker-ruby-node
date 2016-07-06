# Ruby + Nodejs Dockerfile

Ruby + Nodejs docker image

A Dockerfile to create an image for Docker with Ruby and Nodejs.

## What's included
- Ruby 2.3.1
- Nodejs (latest)
- npm

### Building
A prebuild image is available via the public
[Docker Hub Registry](https://registry.hub.docker.com/u/mwallasch/docker-ruby-node/)

    docker pull dmitryzuev/docker-ruby-node

To build the image by yourself just run

    docker build -t="dmitryzuev/docker-ruby-node" github.com/dmitryzuev/docker-ruby-node


### Usage

    docker run -it --rm dmitryzuev/docker-ruby-node

#### Run `ruby`

    docker run -it --rm dmitryzuev/docker-ruby-node ruby

#### Run `node`

    docker run -it --rm dmitryzuev/docker-ruby-node node
