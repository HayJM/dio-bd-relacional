# Banco de Dados Relacional

Um **banco de dados relacional** é um sistema de armazenamento de dados que organiza as informações em tabelas (linhas e colunas), permitindo o relacionamento entre diferentes conjuntos de dados por meio de chaves primárias e estrangeiras. Esse modelo facilita a integridade, a consistência e a flexibilidade na manipulação dos dados.

## Principais Conceitos

- **Tabelas**: Estruturas que armazenam dados em linhas e colunas.
- **Chave Primária**: Identificador único para cada registro em uma tabela.
- **Chave Estrangeira**: Campo que cria um vínculo entre duas tabelas.
- **Relacionamentos**: Ligações entre tabelas (um-para-um, um-para-muitos, muitos-para-muitos).

## Métodos e Comandos Usados nas Aulas

Durante as aulas, foram utilizados diversos comandos SQL para manipulação e consulta de dados em bancos relacionais. Entre os principais métodos e comandos estão:

- **CREATE TABLE**: Criação de tabelas no banco de dados.
- **INSERT INTO**: Inserção de novos registros nas tabelas.
- **SELECT**: Consulta de dados armazenados nas tabelas.
- **UPDATE**: Atualização de dados existentes.
- **DELETE**: Remoção de registros.
- **ALTER TABLE**: Modificação da estrutura de uma tabela (adicionar/remover colunas, chaves, etc).
- **DROP TABLE**: Exclusão de uma tabela do banco de dados.
- **JOIN**: Combinação de dados de duas ou mais tabelas relacionadas.
- **CONSTRAINTS**: Definição de restrições como PRIMARY KEY, FOREIGN KEY, UNIQUE, NOT NULL, etc.

Esses comandos são fundamentais para a criação, manutenção e consulta de bancos de dados relacionais, permitindo a organização eficiente e segura das informações.

## Palavras Reservadas em SQL

As **palavras reservadas** em SQL são termos que possuem função específica na linguagem e não podem ser utilizados como nomes de tabelas ou colunas sem tratamento especial. Elas definem comandos, operadores e estruturas essenciais para a manipulação dos dados.

Exemplos de palavras reservadas e operadores:

- **FROM**: Indica a tabela de onde os dados serão selecionados ou manipulados.
- **WHERE**: Define condições para filtrar registros em consultas ou comandos.
- **DEFAULT**: Define um valor padrão para uma coluna caso nenhum valor seja informado.
- **ORDER BY**: Ordena o resultado de uma consulta conforme uma ou mais colunas.
- **GROUP BY**: Agrupa registros que possuem valores iguais em colunas específicas.
- **HAVING**: Filtra grupos de resultados após o uso do GROUP BY.
- **DISTINCT**: Remove duplicidades, retornando apenas valores únicos.
- **VALUES**: Utilizado para inserir valores em uma tabela.

### Operadores SQL

- **=** : Igualdade. Exemplo: `WHERE idade = 18`
- **<>** ou **!=** : Diferente. Exemplo: `WHERE nome <> 'Ana'`
- **>** : Maior que. Exemplo: `WHERE salario > 1000`
- **<** : Menor que. Exemplo: `WHERE idade < 30`
- **>=** : Maior ou igual. Exemplo: `WHERE nota >= 7`
- **<=** : Menor ou igual. Exemplo: `WHERE data <= '2025-09-09'`
- **AND** : Operador lógico E. Exemplo: `WHERE ativo = 1 AND idade > 18`
- **OR** : Operador lógico OU. Exemplo: `WHERE cidade = 'SP' OR cidade = 'RJ'`
- **NOT** : Negação lógica. Exemplo: `WHERE NOT ativo = 0`
- **BETWEEN** : Seleciona valores dentro de um intervalo. Exemplo: `WHERE idade BETWEEN 18 AND 30`
- **IN** : Verifica se o valor está em uma lista. Exemplo: `WHERE estado IN ('SP', 'RJ')`
- **LIKE** : Busca por padrões em textos. Exemplo: `WHERE nome LIKE 'A%'`

Essas palavras e operadores são fundamentais para a construção de instruções SQL e para a filtragem, agrupamento e manipulação eficiente dos dados.
# dio-bd-relacional

---
## Autor

Projeto desenvolvido por Haynner J. M. (HayJM)