# Análise da Aplicação

A aplicação Beedoo QA Challenge permite o cadastro e listagem de cursos.

Durante a análise exploratória foram identificadas duas funcionalidades principais:

- Cadastro de cursos
- Listagem de cursos

O formulário de cadastro possui os seguintes campos:

- Nome do curso
- Descrição
- Instrutor
- URL da imagem
- Data de início
- Data de fim
- Número de vagas
- Tipo de curso


A estratégia de testes foi baseada em cenários positivos, negativos e testes de limite para validar o comportamento da aplicação diante de diferentes entradas de dados.

## Comportamento dinâmico identificado

Durante a análise da aplicação foi identificado um comportamento condicional no formulário de cadastro:

- Quando o tipo de curso é selecionado como **Online**, o campo **Link de inscrição** é exibido.
- Quando o tipo de curso é **Presencial**, o campo não aparece.

Esse comportamento indica uma lógica dinâmica de interface que deve ser validada nos testes.
