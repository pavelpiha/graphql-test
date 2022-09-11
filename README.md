## Installation

Requires [Node.js](https://nodejs.org/) v14+ to run.

Install the dependencies and start the server.

```sh
npm i
node app
```

Open your browser at http://localhost:4201/graphql and you will be presented with an interactive console.

## Query example

```sh
{
  characters(offset: 2, limit:3) {
    count
    characters {
      name
      homeworld
      species
    }
  }
  species(name:"Human") {
    classification
    homeworld
  }
}
```
