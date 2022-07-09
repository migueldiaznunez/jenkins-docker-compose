# Jenkins Docker Compose

## Requirements

 - https://www.docker.com/

## Init

Start

```
$ docker compose up -d
```

Stop

```
$ docker compose stop
```

## Config Jenkins Agent

https://www.jenkins.io/doc/book/using/using-agents/#configuring-agents-with-docker

Agent name: JenkinsAgent
Workdir: /home/jenkins/agent
Set the token in .env file in JENKINS_AGENT_TOKEN