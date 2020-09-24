# Node.js set up with Docker

### Requirements:

Docker and Docker Compose

### Run:

-- Only with Dockerfile:

    $ docker build -t gabriel/dockernode . (unique name)

    $ docker run -p 3000:3000 -d gabriel/dockernode

-- With Docker Compose:

    $ docker-compose up