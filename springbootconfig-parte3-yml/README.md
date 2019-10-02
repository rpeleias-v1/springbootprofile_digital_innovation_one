<h2>Exercício Juntos - Spring Boot: Profiles e Configurações</h2>


Projeto desenvolvido do tópico Exercício juntos, referente às parte 2 e 3 da aula sobre  **Profiles e Configurações com Spring Boot**, gravado para a Digital Innovation One.

Na parte 2 da aula, foram desenvolvidos os seguintes passos:

* Migração dos arquivos application-dev.properties e appliction-prod.properties para o formato YAML
* Execução do projeto no terminal
 

O projeto consta com todos os passos desenvolvidos acima.

Para executar o projeto no terminal com o profile **dev** como padrão, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080
```


Na parte 3 da aula, foram desenvolvidos os seguintes passos:

* Execução do projeto no terminal com a passagem da porta a ser executada como argumento:

```shell script
mvn spring-boot:run -Dserver.port=8085
```

* Execução do projeto no terminal











