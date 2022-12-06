# Quarkus - Hello World

### Sobre
O projeto visa apresentar uma simples aplicação expondo o funcionamento do framework de Java Quarkus.
Para criar uma primeira aplicação utilizando Quarkus podemos seguir o guia [CREATING YOUR FIRST APPLICATION](https://quarkus.io/guides/getting-started), da documentação do framework.

Vídeo de demonstração seguindo os passos: [Quarkus Hello World](https://www.youtube.com/watch?v=zNa1euniN70&ab_channel=Filipe)

### Pré-requisitos
* IDE, como o Visual Studio Code
* [JDK](https://www.oracle.com/java/technologies/downloads/) 11+ com o JAVA_HOME configurado
* [Apache Maven](https://maven.apache.org/download.cgi) instalado corretamente
* [Quarkus CLI](https://quarkus.io/guides/cli-tooling)

Passos:
* Clone o projeto e vá para a pasta do projeto:
```
git clone https://github.com/filipeakafilipe/quarkus-hello-world.git
cd ./quarkus-hello-world/hello-world
```
* Inicie a aplicação:
```
quarkus dev
```
* Após a aplicação iniciar, podemos acessá-la em `http://localhost:8080/`. Ao clicarmos em `VISIT THE DEV UI`, somos redirecionados para uma interface simplificada, `http://localhost:8080/q/dev/`, da aplicação, que reúne diferentes ferramentas, como o Swagger. Podemos clicar em `Swagger UI`, em `SmallRye OpenAPI`, para sermos direcionados para a interface do Swagger, `http://localhost:8080/q/swagger-ui/`, e vermos os endpoints da API.
