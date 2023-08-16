# ES3A3
Eng Software III

Engenharia de Software 3

Aula 2 – Exercícios

1. Nome do projeto, integrantes do projeto;
Beatriz 

2. Defina a visão geral de um projeto de software para web;
Aplicação para web que apresenta diferentes pôsteres de um filme ou série.
 Utiliza a API do TheMovieDatabase,

3. Descrição dos serviços fornecidos aos usuários;
Variedade de opções de pôsteres oficiais de um filme ou série.

4. Escolher API de dados para acessar informações;
TheMovieDatabase

5. Apresentar as informações de plataforma do projeto de software;
Website desenvolvido com linguagem de programação Java;
Servidor API de database de filmes desenvolvido com NodeJS;


6. Apresentar as especificações de requisitos do projeto de software;
- O Website deve fornecer os posteres disponíveis dentro da API do TMBD a partir de pesquisa;
- O Website deve apresentar barra de pesquisa para que usuário mande solicitação;
- O Website deve apresentar mensagem de erro caso não seja encontrado nenhum resultado a partir da busca;
- O Website deve exibir os posteres em 4 colunas;
- O Website deve ter a opção de ampliar o poster ao ser selecionado.

7. Apresentar a descrição dos dados do projeto de software;
Servidor Web
-
-
-

API
- NodeJS
- ExpressJS
- EJS

8. Criar e incluir o histórico de versões do projeto;
v1.0 15-08-2023

-------------------------------------------------------------------------------------------
Aula 3 – Exercícios

9. Com relação as decisões de Projeto de Arquitetura responda as 9 questões do slide 10:
I. Existe uma arquitetura genérica de alguma outra aplicação que pode servir de modelo para o sistema que está sendo projetado?
Sim o servidor de API será desenvolvidos com a linguagem nodejs e arquitetura das aplicações serão em formato HTTPweb através de requisições GET e POST através do Express NodeJS
II. Como o sistema será distribuído entre os servidores?
Quando o servidor web receber um requisição do usuário, é executada uma solicitação de pesquisa ao servidor de API e será exibido no Servidor Web imagens referentes a pesquisa.
III. Que padrões ou estilos de arquitetura podem ser usados?
REST e Cliente/Servidor.
IV. Como os componentes do sistema serão decompostos em subcomponentes?

V. Que estratégia será usada para controlar o funcionamento dos componentes do sistema?
VI. Qual a melhor organização de arquitetura para satisfazer os requisitos não funcionais do
sistema?
VII. Como o projeto de arquitetura será avaliado?
VIII. Como a arquitetura do sistema deve ser documentada?

10. Descreva o tópico sobre a Introdução da Documentação do Projeto de Arquitetura;
O objetivo deste projeto é desenvolver uma aplicação para web que apresenta posteres de filmes utilizando API do TheMovieDatabase a partir de pesquisa 

12. Apresente a descrição da Representação Arquitetural do Documento do Projeto de Arquitetura;

13. Apresente a descrição dos Objetivos e Restrições da Arquitetura do Documento do Projeto de
Arquitetura;

v1.1 15-08-2023
