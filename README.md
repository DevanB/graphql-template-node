# graphql-template-node

![](https://imgur.com/eMpNw0e.png)

Boilerplate for a scalable, production-ready GraphQL gateway server.

For a boilerplate that includes authentication see [graphcool/graphql-boilerplate](https://github.com/graphcool/graphql-boilerplate)

## Features

* Database (via [Graphcool](https://graph.cool))

## Getting started

#### Requirements

* Node 8 (or higher)
* Graphcool CLI (Get it via `npm i -g graphcool@alpha`)
* GraphQL CLI (Get it via `npm i -g graphql-cli@beta`)
* Optional: GraphQL Playground desktop app (Download [here](https://github.com/graphcool/graphql-playground/releases))

#### Setup your project

```sh
# 1 .From your root directory of choice execute:
graphql create [project-name]

# 2. Choose the "Minimal (Node.js, DB) option

# 3. Navigate to the new project
cd [project-name]

#4. Deploy the Graphcool database
graphcool deploy
```

#### Launch the local server

```sh
# Start server (runs on http://localhost:4000)
yarn start

# Open Playground to explore GraphQL API
yarn playground
```

## Docs

### Commands

* `yarn start` starts GraphQL server
* `yarn debug` starts GraphQL server in debug mode (open [chrome://inspect/#devices](chrome://inspect/#devices) to debug)
* `yarn get-schema` downloads the GraphQL schemas to `schema/*.graphql`
* `yarn playground` opens the GraphQL Playground
