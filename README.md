# Aloompa Coding Challenge: GraphQl API

### Description:

Create a GraphQL API to query apps, events, and stages using this [data set](https://assets.aloompa.com.s3.amazonaws.com/rappers/hiphopfest.json).

Your project must use Node (TypeScript or JavaScript) for the query resolvers. You may use any libraries or frameworks as dependencies, but the code inside the project must be your own.

### API Requirements:
- [x] You should be able to list all of the apps
- [x] You should be able to query a single app
- [x] You should be able to list all the stages
- [x] You should be able to query a single stage
- [x] You should be able to search the stages by name
- [x] You should be able to list all of the events
- [x] You should be able to query a single event
- [x] You should be able to search the events by name
- [x] You should be able to query the events that occur between two dates
- [x] You should be able to list all of the events in an app
- [x] You should be able to list all the stages in an app
- [x] You should be able to get the stage in an event
- [x] You should be able to list the events at a stage
- [x] You should be able to add, update and remove all entities

### Extra Credit:
- [x] Your project is deployed to AWS
- [x] Your repo has a README
- [ ] You use TypeScript  ([Typescript Solution Here](https://github.com/thejmdw/graphql-challenge-typescript))

---

# JavaScript Solution


### Technologies Used

![](https://img.shields.io/badge/Node.js-43853D?style=for-the-badge&logo=node.js&logoColor=white) ![](https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E) ![Apollo-GraphQL](https://img.shields.io/badge/-ApolloGraphQL-311C87?style=for-the-badge&logo=apollo-graphql)

### Running the API

### **AWS

1. Click [Here](https://skeshla775.execute-api.us-east-1.amazonaws.com/dev/) to go straight to the API and start exploring with Apollo Studio.

### **Locally
#### Prerequisites

1. Install [Node.js](https://nodejs.org/en/)

#### Installation

1. Clone this repository and change to the directory in the  terminal.
    ```
    git clone git@github.com:thejmdw/graphql-challenge.git
    cd graphql-challenge
    ```
2. Install dependencies.
    ```
    npm install
    ```
3. Start server.
    ```
    node index.js
    ```
    or
    ```
     npm start
    ```
4. Point browser to [http://localhost:4000](http://localhost:4000) to start exploring the graph with Apollo Studio.
