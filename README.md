# bds-dslearn

Projeto DSLearn do Bootcamp Dev Superior.

Este projeto corresponde ao Back-End, desenvolvido em Java (Spring Boot), de um sistema de Ensino a Distância. 

Desenvolvido utilizando Spring Boot, o Back-End do projeto foi concebido utilizando as melhores práticas em arquitetura de API java, sendo dividido nas seguintes camadas:

- Resource: Classes de Endpoints, onde são recebidas as requisições dos usuários.
- DTO: Classes que montam o conteúdo e o formato das informações que serão trafegadas entre o Cliente e o Servidor, trazendo os seguintes benefícios.
  - Recebimento e envio somente da informação necessária.
  - Evitando o contato direto à camada de acesso ao Banco de Dados e seu contexto de persistência.
  - Enviando respostas ao cliente em um formato padronizado e amigável.
- Repository: Camada de Acesso aos dados, padrão Repository do Spring Boot.
- Entity: Classes de Entidades do Banco de Dados
- Service: Classes de Serviços quem fazem o 'meio-de-campo' entre as Classes Resource e Repository.
