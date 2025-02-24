# GhostFormsService
## About
GFS is course project from ITransition, in Idea it was social media about tests/polls (like in google forms)
It is still incomplete, you can see what I didn't add yet in Futures section

## Dependencies
- docker

## Installation
This project is docker based, so installation is pretty simple:

- First clone this repository with submodules
```sh
    git clone https://github.com/Vlvin/GFS_Docker --recursive
```
- Then in cloned repository start project with
```sh
    docker compose up --build
```

after that, you'll got front-end running on localhost:3000, backend - on localhost:3001 and database on localhost:3306

you can change default backend url, go to dockerFiles/.env and set REACT_APP_BACKEND_URL to your backend url and REACT_APP_BACKEND_PROTOCOL if you plan to use something different from https

you can also change JWT configurations, go to dockerFiles/application.json in "JWT" section

## Futures
- actual Submit on form
- ability to create post using frontend gui
- ability to like post
- comments
- more robust search system

