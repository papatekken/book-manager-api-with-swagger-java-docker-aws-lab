# Building and Deploying a Java application with Docker

Tech Returners Execrise 

Allan Yip

##Solution - Following steps have been done

1)create JAR file with mvn command

2)create image with docker locally

3)send project with docker file to AWS and deploy

4)update application profile to change database from h2 to a mySQL database at RDS, create JAR and deploy it to AWS again.

5)screenshot file produced and located in folder '\screenshot'

## Introduction
This repository is designed to guide you through containerising a Spring boot application using [Docker](https://www.docker.com/).

It also covers instructions for deploying your containerised application to Amazon Web Services.

The application itself is a sample Java Spring book manager API that allows users to manage books.

If you have created your own Java Spring API, the instructions here can also be utilised to containerise and deploy your own application 🙌

### Pre-Requisites
- Java SE Development Kit 11
- Maven

For deployment you'll also need:

- An Amazon AWS account

## How to Get Started

1. Fork this repo to your Github and then clone the forked version of this repo
2. Work through the activities in the activities folder starting with [Activity 1](./activities/activity_1.md).