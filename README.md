# Teste para desenvolvedor .NetCore

Esse é um teste para que possamos avaliar seus conhecimentos técnicos em .net core e qualidade do código. Mais importante do que terminar o teste por completo, é entendermos a linha de raciocinio e as praticas de qualidade utilizadas!

##  Desenvolvimento
Criar uma API que permita:
- Incluir uma pessoa;
- Consultar uma pessoa pelo identificador;
- Consultar uma pessoa a partir de um dos filtros (Nome / CPF / Data / Pais / Estado / Cidade) (Nenhum filtro é obrigatório)
- Alterar uma pessoa;
- Excluir uma pessoa;

O cadastro de pessoas possui os seguintes campos:
- Nome (Obrigatório)
- CPF (Obrigatório e único)
- Data de Nascimento (Obrigatório)
- Pais Nascimento (Obrigatório)
- Estado Nascimento (Obrigatório)
- Cidade Nascimento (Obrigatório)
- Nome do Pai (Opcional)
- Nome do Mãe (Opcional)
- Email (Obrigatório)

## Entregaveis
Deve ser enviado um link de algum repositório GIT com o projeto

## Requisitos
- Seguir o padrão RESTFUL
- Utilizar .net core 3 ou superior
- README.md com o passo a passo para executar o projeto

## Diferenciais
- Entity Framework
- Migrations
- Swagger
- Testes unitários
- Docker