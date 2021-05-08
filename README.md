# Dockerized Flask App

## Table of Contents

- [About](#about)
- [Getting Started](#getting_started)

## About <a name = "about"></a>

This app is a demonstration on how to dockerize a web application using flask and docker

## Getting Started <a name = "getting_started"></a>

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See [deployment](#deployment) for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them.

```
docker build
```

### Installing

A step by step series of examples that tell you how to get a development env running.

Say what the step will be

```
docker build -t <YOUR_USER_NAME>/myfirstapp .
```


```
docker run -p 8888:5000 --name myfirstapp <YOUR_USER_NAME>/myfirstapp
```