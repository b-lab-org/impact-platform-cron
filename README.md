# Impact Platform: Cron
[Docker](https://www.docker.com/) container for [Cron](https://en.wikipedia.org/wiki/Cron)

## Overview
Use with the [data container](https://github.com/b-lab-org/impact-platform-data). Runs the Laravel [Scheduler](https://laravel.com/docs/master/scheduling). Based on [raphiz/docker-ubuntu-cron](https://github.com/raphiz/docker-ubuntu-cron).

## Docker-Compose Usage
```
cron:
    build: impactbot/impact-platform-cron
    volumes_from:
      - data
```
