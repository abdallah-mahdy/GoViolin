# GoViolin 🐱‍🏍

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
