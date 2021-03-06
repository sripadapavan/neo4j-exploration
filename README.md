# An Example GraphQL + Neo4j Web App 

This repository demonstrates how to implement a graph-based web application using Neo4j. It is written in Kotlin and exposes a GraphQL interface. It is based on a blog post from [Excuse The Disruption](http://excusethedisruption.com/secret-sauce-web-app-kotlin-neo4j-graphql/)

The application was written using:

- [Kotlin](https://kotlinlang.org/)
- [Neo4j](https://neo4j.com/)
- [Spring Boot](https://projects.spring.io/spring-boot/)
- [GraphQL](http://graphql.org/)
- [GraphQL Tools](https://github.com/graphql-java/graphql-java-tools)

To build and run the application locally, from the repository root:
```
gradlew run
```

Then load `http://localhost:5000/graphiql.html` and start playing around in GraphiQL
