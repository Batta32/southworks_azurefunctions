# Azure Functions with Docker

This is a simple project of Azure Functions using Docker for SOUTHWORKS Tech Challenge.
You can see a nice blog explaining step by step this project here https://medium.com/@martinbatta32/building-an-azure-functions-with-docker-d014c5711d13.

## Getting Started

Just clone this GitHub Repository on your local machine, and follow the blog how to run it!

### Prerequisites

To run this project you have to have installed:
* Node.js 8.5 or greater.
* Azure Functions Core Tools.
* Docker running.

### Demo

Once you clone this repository, open a terminal and follow these steps:

```
> docker build -t httptriggerjs .
```

```
> docker run -p 8080:80 httptriggerjs
```

## Built With

* macOS High Sierra 
* Node.js
* JavaScript
* Azure Functions
* Docker

## Authors

* **Martin Battaglino** - *Initial work* 

