# GoViolin 🐱‍🏍
Table of Contents
==================

* [GoViolin 🐱🏍](#goviolin-)
   * [Description <g-emoji class="g-emoji" alias="monocle_face" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f9d0.png">🧐</g-emoji>](#description-)
   * [Prerequisites](#prerequisites)
   * [Build and Run <g-emoji class="g-emoji" alias="rocket" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f680.png">🚀</g-emoji>](#build-and-run-)
   * [Tools &amp; Technologies used <g-emoji class="g-emoji" alias="hammer_and_wrench" fallback-src="https://github.githubassets.com/images/icons/emoji/unicode/1f6e0.png">🛠</g-emoji>](#tools--technologies-used-)
   * [How the CI/CD pipeline works ?](#how-the-cicd-pipeline-works-)
   * [Jenkins workflow](#jenkins-workflow)



## Description 🧐

GoViolin is a web app written in Go that helps with violin practice.

Currently hosted on Heroku at https://go-violin.herokuapp.com/

GoViolin allows practice over both 1 and 2 octaves.

Contains:

- Major Scales
- Harmonic and Melodic Minor scales
- Arpeggios
- A set of two part scale duet melodies by Franz Wohlfahrt

## Prerequisites

- [install go](https://golang.org/doc/install)
- [(Optional) install docker](https://docs.docker.com/engine/install/)
- [(Optional) install jenkins](https://www.jenkins.io/doc/book/installing/)
- Clone the repo on your machine
  ```bash
  git clone https://github.com/abdallah-mahdy/GoViolin
  ```

## Build and Run 🚀

- create go.mod file

```bash
  go mod init
```

- build the project

```bash
    go build -o goviolin .
```

- Run the project

```bash
    ./goviolin
```

- (Optional) if you prefer Docker, run the following commands

```bash
    docker build -t GoViolin .
    docker run -d -p 8080:8080 GoViolin
```

- (Optional) use docker-compose

```bash
    docker-compose up -d
```
## Tools & Technologies used 🛠
* Go programming language
* Docker
* Jenkins 
* Kubernetes
## How the CI/CD pipeline works ?
![devops](https://user-images.githubusercontent.com/51873396/119872868-37c02800-bf24-11eb-82fd-3747780f9c97.png)

## Jenkins workflow
![jenkins_pipline](https://user-images.githubusercontent.com/51873396/119893029-26cee100-bf3b-11eb-95a6-70222087e126.png)

also received an email from the pipeline
![Capture](https://user-images.githubusercontent.com/51873396/119894139-85488f00-bf3c-11eb-849c-9a7ef3b1d21e.PNG)
