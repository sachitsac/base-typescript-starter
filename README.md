# Introduction

Just a basic template starter for a new typescript project

### Using npm

```
# if you have nvm on your system
nvm use

# install dependencies
npm i

# testing the app
npm test

# lint
npm run lint

```

### Using docker

Note, the entry point to docker is npm. So you can run any command using the container that you would normally using npm. Just the commands don't need to start with npm. See examples below.

```
# Build the docker image
docker build -t template-stack .

# run tests
docker run -it template-stack test

# run lint
docker run -it template-stack run lint

```
