# GraphQLServerNode

Graph QL Server Example Using Express and Node

Run Local Sever :

> npm run json:server

Run Application Server

> npm start

# Sample Input for Single Entity

## Input

```
{
  customer(id:"5"){
    name
    age
    email
  }
}

```

## Output

```
{
  "data": {
    "customer": {
      "name": "Jen Thompson",
      "age": 22,
      "email": "jen@gmail.com"
    }
  }
}
```

# Sample Input for All Entity

## Input

```
{
  customers {
    name
    age
    email
  }
}


```

## Output

```
{
  "data": {
    "customers": [
      {
        "name": "John Doe",
        "age": 35,
        "email": "jdoe@gmail.com"
      },
      {
        "name": "Steve Smith",
        "age": 25,
        "email": "steve@gmail.com"
      },
      {
        "name": "Sara William",
        "age": 20,
        "email": "sara@gmail.com"
      },
      {
        "name": "Tom Jones",
        "age": 23,
        "email": "tom@gmail.com"
      },
      {
        "name": "Jen Thompson",
        "age": 22,
        "email": "jen@gmail.com"
      }
    ]
  }
}

```
