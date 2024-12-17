# POO - Projeto Banco

#### Projeto: Integrar um banco de dados PostgreSQL ao back-end e desenvolver um front-end

#### Abaixo segue as instruções para rodar este projeto no VSCode:

- Clonar repositório;
- Dentro da pasta *banco*, execute o comando `mvn install` para instalar as dependências do back-end;
- No back-end, acesse o arquivo `src/resources/application.properties` e ajuste a *URL*, *nome de usuário* e *senha* conforme o banco de dados que você está utilizando;
- No back-end, abra o arquivo `src/java/allContas/WebConfig.java` e altere a configuração de allowedOrigin para a porta do front-end que você está usando;
- No front-end, acesse a pasta front-end e execute `yarn install` ou `npm install` para instalar as dependências necessárias;
- No arquivo HTML, utilize a extensão *Live Server* para executar o projeto no navegador;
- No back-end, vá até `src/allContas/AcessoADado.java` e execute o comando *run java* para rodar a aplicação.


- *OBS:* Projeto reupado devido a erros em uma versão de test do Windows 11.
