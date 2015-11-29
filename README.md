# sample-app

*An example repo for running LFE and custom LFE apps in Docker*

## Introduction

This repo is featured in
[this](http://blog.lfe.io/tutorials/2014/12/07/1837-running-lfe-in-docker/) as
well as [this one](). The former goes into more detail on how to run LFE in
docker, which the second one is an update showing how to use the Docker image
genereated from this repo as quickly as possible.

## Use

To run the Docker image you need to have docker installed and running. Then
simply run the following:

```bash
$ docker run lfex/lfe-yaws-sample-app
```

## Builing

If you should choose to build the Docker image yourself instead of getting it
from Docker Hub:

```bash
$ git clone git@github.com:oubiwann/docker-lfe-yaws-sample-app.git
$ make docker-build
$ make docker-run
```

For more details, you'll just need to read the blog posts linked above ;-)
