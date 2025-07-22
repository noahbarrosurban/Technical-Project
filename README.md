# Sistema de Gerenciamento de Equipamentos de TI  

> "Educação nunca foi despesa. Sempre foi investimento com retorno garantido." — Arthur Lewis

![java](https://badgen.net/badge/Java/17/red?scale=1.2) ![kotlin](https://badgen.net/badge/Kotlin/1.9.25/green?scale=1.2) ![spring-boot](https://badgen.net/badge/Spring%20Boot/3.3.3/blue?scale=1.2) ![react](https://badgen.net/badge/React/18.2.0/blue?scale=1.2) ![node](https://badgen.net/badge/Node.js/18.x/orange?scale=1.2)

**Olá, Dev!**  

Este repositório contém uma atividade desenvolvida para o meu TCC do curso técnico em Desenvolvimento de Sistemas, com objetivo de simplificar o gerenciamento dos equipamentos de TI no ambiente corporativo, facilitando o cadastro, atualização e visualização dos dados de forma organizada. A aplicação foi construída em em Kotlin com o uso do framework Spring, no backend, e React, no frontend.  

## Pré-Requisitos  

### Backend  

- [Java JDK 17](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html)

- [Node.js](https://nodejs.org/en/download/)
    
- [Docker](https://www.docker.com/products/docker-desktop/)

- [IntelliJ IDEA](https://www.jetbrains.com/idea/download/)
  
- [Visual Studio Code](https://code.visualstudio.com/download)
 
## Ambiente de Desenvolvimento  

### Configuração do Backend  

1. **Inicie o contêiner Docker**

    Para testar a aplicação com o banco de dados PostgreSQL, inicie o Docker Desktop. 
    
    Com o projeto devidamente armazenado localmente, abra um terminal na pasta `Technical-Project -> backend`.
    
    ```shell
    docker compose up
    ```

2. **Execute o Projeto**

    Abra o projeto backend utilizando o IntelliJ IDEA e localize a classe `EquipmentsApplication` (marcada com `@SpringBootApplication`).

    Clique com o botão direito na classe e selecione `Run EquipmentsApplication.main()`.


### Configuração do Frontend  

1. **Instale as Dependências**

    Abra o projeto frontend utilizando o Visual Studio Code e abra um novo terminal.

    ```bash  
    npm install  
    ```  

3. **Inicie o Frontend**
   
    ```bash  
    npm start  
    ```  

   Você deve ver a aplicação rodando em [localhost:3000](http://localhost:3000).  

## Documentação

Após o projeto backend iniciar, você pode acessar a interface do Swagger em: [localhost:8080](http://localhost:8080/swagger-ui/index.html).

### Onde obter ajuda?

Para sanar quaisquer dúvidas, procure o Engenheiro de Software responsável pelo projeto.
