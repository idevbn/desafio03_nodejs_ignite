<h1 align="center">
  <strong>Third challenge of <a href="https://rocketseat.com.br/"><em>Rocketseat</em>'s</a> Bootcamp - Ignite</strong>  
</h1>

<br>

<div align="center">
  <img src="https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/-jest-%23C21325?style=for-the-badge&logo=jest&logoColor=white">
  <img src="https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white">
</div>

<br>

<div align="center">
  <a href="#about"><em>About</em></a> • <a href="#techs"><em>Technologies</em></a> • <a href="#run"><em>Running</em></a>
</div>

<br>

<a id="about"></a>

## :bulb: About the Project

<p>This project consists in a simple Repository application using <strong>Javascript</strong> (<em>NodeJS</em>).
<br>
The Repository is an object containing: id, title, url, techs and likes.
<br>
In this application we can do a CRUD operation, with respectives status code, and we also apply the concept of middleware.
<br>
In our app we can get likes on the registered repositories and the amount of likes is incremented by one. The id must be a valid <em><a href="https://en.wikipedia.org/wiki/Universally_unique_identifier" target="_blank">uuid</a></em> and we also approach the request/response manipulation cycle.
<br>
<strong>OBS:</strong> The data is not saved in a database, instead we use an array to momentarily store information.

<br>

<a id="techs"></a>

## :computer: Technologies

The project includes the following technologies:

- [NodeJS](https://nodejs.org/)
- [Jest](https://jestjs.io/)
- [Yarn](https://yarnpkg.com/)

<br>

<a id="run"></a>

## :memo: Running the project

1. Prequisites:

To run this app on your machine is necessary to have locally installed: **[Node.js](https://nodejs.org/en/)**, **[Git](https://git-scm.com/)** and a package manager such as **[Yarn](https://yarnpkg.com/)**.

2. Cloning this repository:

```sh
  $ git clone https://github.com/idevbn/desafio03_nodejs_ignite
```

3. Running locally:

```sh
  # Installing packages and dependencies
  $ yarn

  # Initializing the server
  $ yarn dev

  # Testing
  $ yarn test

  # Open your browser at the localhost:3333

```
