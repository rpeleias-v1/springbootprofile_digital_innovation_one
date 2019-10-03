<h2>Exercício Juntos - Spring Boot: Profiles e Configurações</h2>


Projeto desenvolvido do tópico Exercício juntos, referente às parte 5 da aula sobre  **Profiles e Configurações com Spring Boot**, gravado para a Digital Innovation One.

Na parte 5 da aula, foram desenvolvidos os seguintes passos:

* Injeção do valor exportado através da variável de ambiente ENV_DB_URL na classe AppController.
* Definição de um valor default junto com a anotação @Value caso a variável de ambiente acima não seja exportada.
* Criação de método para exibir o valor da variável de ambiente no browser.
* Executar projeto no terminal e exibir conteúdo no browser 
 

O projeto consta com todos os passos desenvolvidos acima.

Para executar o projeto no terminal com o profile **dev** como padrão, digite o seguinte comando:

```shell script
mvn spring-boot:run 
```

Após executar o comando acima, basta apenas abrir o seguinte endereço e visualizar a execução do projeto:

```
http://localhost:8080
```






