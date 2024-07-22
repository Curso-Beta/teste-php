# Teste para candidatos à vaga de Desenvolvedor PHP Pleno

Olá caro desenvolvedor, nesse teste analisaremos seu conhecimento geral e inclusive velocidade de desenvolvimento. Abaixo explicaremos tudo o que será necessário.

## Instruções

O desafio consiste em implementar uma aplicação web utilizando o framework PHP Laravel, um banco de dados relacional (Mysql), que terá como finalidade a inscrição de candidatos a uma oportunidade de emprego.

Sua aplicação deve possuir:

- CRUD de vagas:
  - Criar, editar, excluir e listar vagas.
  - A vaga pode ser CLT, Pessoa Jurídica ou Freelancer.
- CRUD de candidatos:
  - Criar, editar, excluir e listar candidatos.
- Um cadidato pode se inscrever em uma ou mais vagas.
- Deve ser ser possível "pausar" a vaga, evitando a inscrição de candidatos.
- Cada CRUD:
  - Deve ser filtrável e ordenável por qualquer campo, e possuir paginação de 20 itens.
  - Deve permitir a deleção de qualquer item de sua lista.
  - Implementar validações de campos obrigatórios e tipos de dados.
- Testes unitários.

## Banco de dados

- O banco de dados deve ser criado utilizando Migrations do framework Laravel, e também utilizar Seeds e Factorys para popular as informações no banco de dados.

## Tecnologias a serem utilizadas

Devem ser utilizadas as seguintes tecnologias:

- Framework Laravel (PHP)
- Docker (construção do ambiente de desenvolvimento)
- Mysql

## Entrega

- Para iniciar o teste, crie um repositório em sua conta git.
- Altere o arquivo readme.md com as informações necessárias para executar o seu teste (comandos, migrations, seeds, etc);
- API Rest JSON para todos os CRUDS listados acima.

## Bônus
- Documentação da Api
- Sempre que uma vaga for pausada, notificar todos os inscritos para a vaga
- Notificação de forma assincrona.
- Permitir deleção em massa de itens nos CRUDs.

## O que iremos analisar

- Organização do código;
- Aplicação de design patterns;
- Aplicação de testes;
- Separação de módulos e componentes;
- Legibilidade;
- Criação do ambiente com Docker.

### Boa sorte!
