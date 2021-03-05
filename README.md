# Todo React App 

Todo React App using GraphQL .

### GraphQL Schema Design for Dgraph


```graphql
type Task {
    ...
}

type User {
    ...
}
```

We represent that in the GraphQL schema shown below:

```graphql
type Task {
    id: ID!
    title: String!
    completed: Boolean!
}

type User {
    username: String!
    name: String
}
```

## Bring up ToDo App

### `npm install`

Install the dependencies needed to bring up the application.

### `npm start`



Runs the Todo application.<br />
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.


