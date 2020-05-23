<h1 align="center">
  Portfolio Website
</h1>

![Gatsby Publish](https://github.com/rmwthorne/rmwthorne.github.io/workflows/Gatsby%20Publish/badge.svg?branch=dev)
![GitHub](https://img.shields.io/github/license/rmwthorne/rmwthorne.github.io)
![GitHub last commit](https://img.shields.io/github/last-commit/rmwthorne/rmwthorne.github.io)

<p align="center">
  <img width="320" height="266" src="./src/images/preview.png">
</p>

<p align="center">
  <a href="http://rmwthorne.github.io/">View Live</a>
</p>

Portfolio website, built on the generous work of [LekovicMilos/gatsby-starter-portfolio](https://www.gatsbyjs.org/starters/LekovicMilos/gatsby-starter-portfolio/), with many thanks.

## Setup

1.  **Install dependencies**

    ```sh
    cd rmwthorne.github.io/
    nvm use 10
    npm install
    ```

2.  **Development**

    ```sh
    gatsby develop
    ```

    This will run a devlopment server at `http://localhost:8000`.

3.  **Deployment**

    Deployment is handled by the github actions in `.github/workflows/main.yml`. Pushes to `dev` cause the files to be built on `master`.
