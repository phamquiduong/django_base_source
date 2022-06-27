## Config env file
- Copy `docker/env.example` file to `docker/.env`
- Update value in `.env` file

Note: `.env` file can include constance for Django system

## PIP
- You can list install python package in `docker/requirements.txt` file

## Start project
```bash
# Cd to docker folder
cd docker

# Build and Run docker in one command
docker-compose up --build -d

# Build and install library
docker-compose build

# Run server
docker-compose up

# If you want run server in background
docker-compose up -d
```

## Thank you so much
