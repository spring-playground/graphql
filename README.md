# graphql
Repository to experiment with Spring and GraphQL

Original context from : https://www.pluralsight.com/guides/java-and-j2ee/building-a-graphql-server-with-spring-boot


POST to http://localhost:8080

{
  "query": "mutation { newBook( title: \"Java: The Complete Reference, Tenth Edition\", isbn: \"1259589331\", author: 1) { id title } }"
}

{
  "query": "{findAllBooks{id title}}"
}
