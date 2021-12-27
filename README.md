# Demo - spring webflux 

## Stack utilizada
  * Java8
  * spring webflux
  * Spring data
  * dynamodb
  * junit
  * sl4j
  * reactor
  
 

### Executar dynamo: 

| Descrição                         | Comandos/Endpoints
|-----------------------------------|-----------------------------------------------------------------------------|
|na pasta em que o jar está baixado | java -Djava.library.path=./DynamoDBLocal_lib -jar DynamoDBLocal.jar -sharedDb|
|para listar as tabelas criadas | aws dynamodb list-tables --endpoint-url http://localhost:8000|
|documentacao gerada pela aplicação: swagger| http://localhost:8080/swagger-ui-heroes-reactive-api.html|