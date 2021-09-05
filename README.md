# Flask simple container app

The most simples flask app in container docker.

## Get Started

###  Prerequisites

You need to install docker in your computer.

### Installation

Build your docker image
~~~shell
docker build -t myimage .
~~~

Run your docker container app
~~~shell
docker run -d -p 5000:5000 myimage
~~~

### Usage

After run your open in your browser ``http://localhost:5000/``
