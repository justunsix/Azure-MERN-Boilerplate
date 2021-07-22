# Azure-MERN-Boilerplate

A very basic boilerplate for an Azure ready MERN app

The tutorial for deploying this boilerplate can be found here:
<https://medium.com/@tuna.sogut/how-to-deploy-a-mern-stack-app-to-azure-via-continuous-integration-a3a551526e26?sk=0fc4fa9d7c7072ad7e95b94d7e5733e4>

## About The Project

### Built With

- [MERN](https://www.mongodb.com/mern-stack)
- [Node JS](https://nodejs.org/en/)

[![Gitpod ready-to-code](https://img.shields.io/badge/Gitpod-ready--to--code-blue?logo=gitpod)](https://gitpod.io/#https://github.com/justintungonline/)

## Getting Started

### Prerequisites

- npm
- yarn

### Installation

In the file `routes/new-index.js` change:

```js

// The connection string the database to use your connection. You can create free one from MongoDB Atlas (https://www.mongodb.com/cloud/atlas) and create a database and initial collection.
var url = "mongodb+srv://<username>:<password>@<cluster>-vgz77.azure.mongodb.net/test?retryWrites=true&w=majority";
...
// Update the database name to name of your database.
  var dbo = db.db("<database>");
```

```sh
cd <repository directory>
npm install
# Optionally fix vulnerabilities with npm audit fix

cd client
yarn install
npm run build
```

In the `client` directory, run `npm run build` to build whenever you have made changes.

```

## Usage

## Roadmap

- Azure App Service deployment instructions

## License

Distributed under the MIT License

## Contact

[Justin Tung on GitHub](https://github.com/justintungonline/)

## Acknowledgements

- [Best README template](https://github.com/othneildrew/Best-README-Template/blob/master/README.md)
