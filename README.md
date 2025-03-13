# Laboratório de queries SQL no jupyter notebook

Este projeto teve como objetivo a prática de diferentes pesquisas em banco de dados usando linguagem SQL.

## Conteúdo

- [Fonte dos Dados](#-fonte-dos-dados)
- [Visão Geral do Projeto](#visao-geral-do-projeto)

### Fonte dos Dados

O dataset usado neste projeto foi extraído do "Portal de Dados Abertos" do Governo Federal no link: "https://dados.gov.br/dados/conjuntos-dados/usinas-termeletricas-por-tipo1", identificado como "usina-termeletrica-tipo.csv".

### Visão Geral do Projeto

#### Armazenagem dos Dados Limpos

Os dados limpos fora armazenados  em um banco de dados SQL do tipo SQLite utilizando linquagem SQL por meio do pacote python sqlite3.
As demais manipulações de dados para o BD SQLite foram feitas usando o pacote pandas em conjunto com o pacote sqlalchemy.

#### Declarações SQLs envolvidas

- Declarações: SELECT, FROM, WHERE, GROUP BY, ORDER BY, HAVING;
- Funções de agregação: COUNT, SUM, MIN, MAX, AVG;
- Operadores: AND, OR, NOT.

#### Linguagens e Pacotes Utilizados

- Python: pandas, sqlite3, sqlalchemy.
- SQL: extração de dados via query.
