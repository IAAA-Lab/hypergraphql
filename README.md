# graphql-sparql-java
This is a working repository for a GraphQL server over a SPARQL endpoint, implemented in Java.

The server runs at http://localhost:8890 and for testing purposes is currently pointing to the following SPARQL endpoint: 
http://ec2-52-23-193-209.compute-1.amazonaws.com:5820/photobox/query

The GraphiQL IDE is served at: http://localhost:8890/graphiql.html



A valid JSON-LD object is attached in the "extensions" section of the GraphQL response, as the value of the "json-ld" property. 


