---
title: Automated Cast Receiver Testing
date: 2019-05-21 09:57:00 -0500
tags: chromecast, cast, testing
author: brandonrisell
layout: blog
---

## Intro

I've recently been doing Google Cast receiver development and found the official documentation and stance on testing rather lacking. I dove into several great projects from the community and was able to get automated testing working.

## Receiver and sender we'll be using

Introduce and go through a very simple receiver and a very simple sender that we'll be using during this tutorial.

_I need some kind of media that I can host somewhere. Maybe grab an open/free endpoint for big buck bunny?_

_Could this section be based on two previous tutorials on creating a very basic receiver and sender?_

_If so, start with a sender that uses a default receiver?_

## Official docs

Talk about what the official docs receommend for testing

## Unit Testing

Go through setting up unit testing for receiver development

## Emulator

This will be a large section broken up into smaller sections around specific tasks

### Recording scenarios

Walk through recording scenarios with the emulator tools

### Running the emulator

Run the emulator locally using the scenario we just recorded

### Run TestCafe on the receiver locally

Now Setup TestCafe to run locally against the receiver

## Docker and CI

Take what we've done above, and put it into a docker container

### TestCafe has a docker container we can use

Grab the testcafe docker container and run it

### Run the emulator on the docker container

We'll need to customize the container a bit in order to run the emulator.

### Run a web server for the receiver

We'll want to host this version of the receiver for doing CI.

### Setup TestCafe/tests to run on the container

Now finish things out and get the tests running on the container.

## Hook into CI

Now we want to run the docker tests as part of a build process. Probably see if I can use a Google/Firebase build service?
