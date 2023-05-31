<h1 align="center">  Challenge Frontend Mercado libre </h1>

<hr>

## Table of Contents
1. [General Info](#General-Info)
2. [Technologies](#Technologies)
3. [Installation](#Installation)


## General Info
***
This project is the result of a proposed challenge to generate a small application that consumes the Mercado libre api and displays the results of the products obtained on screen.

## Technologies
***
A list of technologies used within the project:
* [Nodejs](https://nodejs.org): Version 18.12 
* [React](https://react.dev): Version 18.2
* [Vite](https://vitejs.dev): Version 4.3
* [TypeScript](https://www.typescriptlang.org/): Version 5.0

## Installation
***
The project is composed of two directories Api and frontend, these directories are submodules of other projects. To get the project locally follow the following steps 
```bash 
$ git clone --recursive  git@github.com:matyaspr/frontend-meli.git
```

> if this form does not work use for each of the projects
```bash 
$ git clone git@github.com:matyaspr/frontend-meli.git
$	git submodule init
$	git submodule update
```

### Api
```
$ cd Api
$ create a file .env, specify the following values, for example:

    PORT=3001
    # api mercadolibre
    MELI_API=https://api.mercadolibre.com

$ npm install
$ npm run dev
```
### frontend
```
$ cd frontend
$ create a file .env, specify the following values, for example:

    VITE_API_URL=http://localhost:3001

$ yarn
$ yarn dev
```







