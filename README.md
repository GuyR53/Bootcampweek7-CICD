# Goals:





<img width="615" alt="Screen Shot 2022-04-09 at 18 57 37" src="https://user-images.githubusercontent.com/93793111/162582180-fe17cb3a-1d24-4279-b69e-03e77e7a7cd2.png">




1. Create an Azure DevOps Organization.
2. Create a CICD (yaml) using Azure Pipelines.
3. CI pipeline should trigger automatically on every commit.
4. Use Azure Artifacts to store your build Artifacts.
5. Create a CD Job using Yaml job (yaml).
6. Configure your CD stage to deploy to Staging using Continuous Deployment.
7. Configure your CD stage to deploy to Production using Continuous Delivery.
8. In case of making a change to the code and pushing it, it will be automatically deployed to the Staging environment.
9. Deployment to production must consist of a manual approval.


# Node.js Weight Tracker

![Demo](docs/build-weight-tracker-app-demo.gif)

This sample application demonstrates the following technologies.

* [hapi](https://hapi.dev) - a wonderful Node.js application framework
* [PostgreSQL](https://www.postgresql.org/) - a popular relational database
* [Postgres](https://github.com/porsager/postgres) - a new PostgreSQL client for Node.js
* [Vue.js](https://vuejs.org/) - a popular front-end library
* [Bulma](https://bulma.io/) - a great CSS framework based on Flexbox
* [EJS](https://ejs.co/) - a great template library for server-side HTML templates

**Requirements:**

* [Node.js](https://nodejs.org/) 14.x
* [PostgreSQL](https://www.postgresql.org/) (can be installed locally using Docker)
* [Free Okta developer account](https://developer.okta.com/) for account registration, login

## Install and Configuration

1. Clone or download source files
1. Run `npm install` to install dependencies
1. If you don't already have PostgreSQL, set up using Docker
1. Create a [free Okta developer account](https://developer.okta.com/) and add a web application for this app
1. Copy `.env.sample` to `.env` and change the `OKTA_*` values to your application
1. Initialize the PostgreSQL database by running `npm run initdb`
1. Run `npm run dev` to start Node.js

The associated blog post goes into more detail on how to set up PostgreSQL with Docker and how to configure your Okta account.
