# SonarQube in a Docker container.

<img src="https://docs.sonarqube.org/download/attachments/2752841/SONARQUBE44" width="350px" />
<br/>
<img src="https://raw.githubusercontent.com/docker-library/docs/b449be7df57e9ed9086bb5821bfb5d6cdc5d67a4/docker-dev/logo.png" max-width="350px"/>

# Description
Docker compose file to launch an instance of SonarQube in a container.

# Basic usage
Set environment variables:
```
$ export DOCKER_SONAR_DB_USER=dbuser
$ export DOCKER_SONAR_DB_PASS=dbpassword
```

Run docker compose:
```
$ docker-compose up -d
```

For more information, go to [official docker documentation](https://docs.docker.com/samples/library/sonarqube/)
