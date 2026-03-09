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

## Comportamentos condicionais identificados

Durante a exploração da aplicação foi identificado que o formulário de cadastro altera dinamicamente os campos exibidos com base no tipo de curso selecionado.

Regras observadas:

- Quando o tipo de curso é **Online**, o campo **Link de inscrição** é exibido.
- Quando o tipo de curso é **Presencial**, o campo **Endereço** é exibido.

Esse comportamento indica que o formulário possui validações condicionais que devem ser consideradas nos cenários de teste.

