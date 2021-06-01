# lamp-on-docker
LAMP stack on Docker for __development__ (php version 7.4.19)

Based on Docker set-ups found in:
- https://github.com/akeneo/pim-community-dev
- https://github.com/sprintcube/docker-compose-lamp


## Quick start / Usage

```shell
git clone git@github.com:Climbman/lamp-on-docker.git

cd lamp-on-docker && rm -rf .git 
```

Copy your application files to `lamp-on-docker/app` directory.

Run `docker-compose up` and your application should be available at `localhost:80`.

## Configuration

