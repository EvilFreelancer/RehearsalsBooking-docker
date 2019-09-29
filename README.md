# Docker Composer for RehearsalsBooking

## How to use

Clone repo

    git clone git@github.com:EvilFreelancer/RehearsalsBooking-docker.git

Switch to folder with sources

    cd RehearsalsBooking-docker

Set (dot)env files

    cp .env.example .env
    cp .env.database.example .env.database

Set docker-compose.yml file

    cp docker-compose.yml.dist docker-compose.yml

Pull containers from Docker Hub

    docker-compose pull

Build from Dockefiles:

    docker-compose build

Start containers

    docker-compose up -d

# Links

* https://github.com/RehearsalsBooking/backend
