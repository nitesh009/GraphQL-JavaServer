# GraphQL-JavaServer

This repo contains basic Graph QL server developed in Java langugage.
To make it up and running in local machine, clone this repo and run below mentioned command.

You can run the app just by executing mvn jetty:run in the directory where pom.xml is located, and Jetty will start on port 8080.

If you now open http://localhost:8080/graphql?query={allLinks{url}} 
you’ll see your very first GraphQL query executing and giving you the result looking like this:

{
  "data": {
    "allLinks": [
      {
        "url": "http://howtographql.com"
      },
      {
        "url": "http://graphql.org/learn/"
      }
    ]
  }
}
