#### This repo is under construction!

# Implementing NodeJS without using NPM

### What is it?

A Boilerplate built in NodeJS without using NPM

### What is needed?

NodeJS (LTS) ie. >= 8.11.3

### How to download?

```sh
git clone https://github.com/faizahmedfarooqui/nodejs.git;
cd nodejs;
```

### How to setup?

Please follow the steps given;
1. Goto the `https/keyGeneration.txt` file in the repository
2. Execute the given command to generate the file `key.pem` & `cert.pem` into the same folder
3. Generate two directory/folders into the root of this repo
    * One should be named `.logs`
    * And one should be named `.data`

### List of things, this repository contains:

* A server to listen to HTTP/HTTPS requests ([View Code](https://github.com/faizahmedfarooqui/nodejs/blob/master/lib/server.js#L26-#L38))
* RESTful API to CRUD and many more for users, tokens & checks
* Router for request methods like GET, POST, PUT & DELETE
* Handlers(ie. controllers) to handle requests & their methods
* A Worker to execute things in background
* A logging logic that logs everything into a *.log file
* A gzip compression logic which compresses older log file
* Local debug environment for the developments in each files
* A Web App with template logic & data interpolation
* Logic to serve static assets to the web-app
