# Tudo sobre Spring Boot

Treinamento sobre Spring Boot (03-09/11/2022)

## Ferramentas necessárias
- Java Development Kit 17 ou 19
    - [Tutorial de instalação e configuração](https://www.youtube.com/watch?v=CMHU5buXvNw)
- [Intellij Community](https://www.jetbrains.com/pt-br/idea/download/)
- [Postman](https://www.postman.com/downloads/): não precisa criar conta.
- Maven: pode ser baixado por meio do próprio Intellij durante a configuração do projeto.
    - Mas você pode seguir o [tutorial de instalação e configuração do Apache Maven](https://www.youtube.com/watch?v=-ucX5w8Zm8s)
- [MySQL Workbench](https://dev.mysql.com/downloads/workbench/): baixar a versão para desenvolvedores.

## O que é Spring Boot?
O [Spring Boot](https://spring.io/projects/spring-boot) é um framework Java open source que tem como objetivo facilitar esse processo em aplicações Java.

## Começando a trabalhar com Spring Boot
Para criar um projeto com Spring Boot do zero, basta usar a ferramenta [Spring Initializr](https://start.spring.io/).
- Selecionar Project: Maven
- Selecionar Language: Java
- Selecionar Spring Boot: versão selecionada por padrão
- Project metadata:
    - Group: com.projeto
    - Artifact: projeto
    - Nome: Projeto
    - Package name: é preenchido automaticamente
    - Packaging: jar
    - Java: aqui, 19, mas pode ser outras versões
- Dependencies
    - Spring Web
    - Spring Boot Dev Tools
- Clicar em `Generate` ou `ctrl` + `enter`

## Conhecendo o projeto
- O Initializr fará o download do arquivo do projeto compactado.
- Descompacte o arquivo e se possível, copie-o para o repositório `Idea Projects` na sua máquina.
- Abra o Intellij e se houver algum projeto aberto, selecione `File` > `Close project`.
- Na parte de boas-vindas do Intellij, selecione `Open`, para abrir o projeto criado no Initializr.
- Selecione seu projeto para abri-lo no Intellij.
- Na raiz do projeto, o arquivo `pom.xml` guarda todas as dependências necessárias para o projeto, como as configurações estabelecidas no Initializr: Spring Web e Spring Boot Dev Tools

## O primeiro "hello, world!"

## Repositories

## Controllers

## Services

## CRUD + verificação

## Banco de dados local H2

## Exceções personalizadas

## Validação no backend

## Mapeamento de banco de dados no Spring Boot

## JPQL queries

## Valor opcional nos parâmetros da request

## Perfis de projeto

## 

