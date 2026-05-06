# QA Portfolio - Testes de API com Postman

Este projeto demonstra a criação de uma suíte de testes de API utilizando o Postman, com foco em organização, boas práticas de QA e validações de resposta.

## Tecnologias utilizadas

* Postman
* API pública JSONPlaceholder

## Estrutura do projeto

* **Posts** → CRUD básico + validações + uso de variáveis
* **Comments** → Testes com query parameters
* **Users** → Validação de estrutura de dados

## O que este projeto demonstra

* Organização por módulos (Posts, Comments, Users)
* Uso de environments (Development e Staging)
* Validação de status code e estrutura de resposta
* Uso de variáveis dinâmicas (ex: ID de post)
* Testes positivos e negativos

## Fluxo implementado (Posts)

1. Criar um post (POST)
2. Validar resposta (status 201 + ID)
3. Salvar ID em variável de ambiente
4. Buscar post criado usando ID dinâmico

## Observação

A API JSONPlaceholder é uma API fake, ou seja, os dados não são persistidos de fato. O foco do projeto é demonstrar técnicas de teste, não persistência real.

## Como utilizar

1. Importar a collection no Postman
2. Importar um dos environments (Development ou Staging)
3. Executar as requisições manualmente ou via Runner

## Objetivo

Este projeto foi desenvolvido com o objetivo de praticar testes de API e demonstrar habilidades iniciais em QA para oportunidades na área.

---
