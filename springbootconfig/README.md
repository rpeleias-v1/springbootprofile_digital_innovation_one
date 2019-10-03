<h2>Exercício Juntos - Spring Boot: Profiles e Configurações</h2>


Projeto desenvolvido do tópico Exercício juntos, referente às parte 1 e 2 da aula sobre  **Profiles e Configurações com Spring Boot**, gravado para a Digital Innovation One.

Na aula, foram desenvolvidos os seguintes passos:

* Criação do projeto com spring.initialzr e importação na IDE.
* Criação de arquivos application.properties para dev e prod.
* Desenvolvimento de classe de configuração de BD e anotação com @Configuration.
* Mapeamento de propriedades com @ConfigurationProperties na classe de configuração acima.
* Métodos para instanciação de Beans de banco de dados para cada ambiente.
* Desenvolvimento de classe para execução no Browser anotada com @RestController.
* Injeção da propriedade app.message na variável appMesagge do Controller com a anotação @Value.
* Criação de método para retornar a mensagem injetada acima.
* Execução do projeto no browser.
 

O projeto consta com todos os passos desenvolvidos acima.

Para executar o projeto no terminal com o profile **dev** como padrão, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080
```


Para executar o projeto com o profile **prod** como padrão, altere a seguinte propriedade no arquivo **application.properties**:

```
spring.profiles.active=prod
```











