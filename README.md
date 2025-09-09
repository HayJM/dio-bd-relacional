# Banco de Dados Relacional

Um **banco de dados relacional** é um sistema de armazenamento de dados que organiza as informações em **tabelas** (linhas e colunas), permitindo o relacionamento entre diferentes conjuntos de dados por meio de **chaves primárias** e **chaves estrangeiras**. Esse modelo garante **integridade, consistência e flexibilidade** na manipulação dos dados.

## Principais Conceitos

- **Tabelas**: Estruturas que armazenam dados em linhas e colunas.
- **Chave Primária**: Identificador exclusivo para cada registro em uma tabela (não permite valores nulos ou duplicados).
- **Chave Estrangeira**: Campo que cria um vínculo entre duas tabelas.
- **Relacionamentos**: Ligações entre tabelas (1:1, 1:N, N:M).
- **Cardinalidade**: Define o número de ocorrências possíveis entre entidades em um relacionamento.
- **Normalização**: Processo de eliminar redundâncias e inconsistências nos dados por meio das formas normais (1NF, 2NF, 3NF, etc.).
- **Subconsultas**: Consultas aninhadas dentro de outras consultas, usadas para filtrar ou calcular resultados intermediários.

## Tipos de JOIN

Os **JOINs** são usados para combinar dados de duas ou mais tabelas:

- **INNER JOIN**: Retorna apenas registros com correspondência em ambas as tabelas.
- **LEFT JOIN**: Retorna todos os registros da tabela da esquerda e os correspondentes da tabela da direita (se existirem).
- **RIGHT JOIN**: Retorna todos os registros da tabela da direita e os correspondentes da tabela da esquerda.
- **FULL JOIN**: Retorna todos os registros de ambas as tabelas, mesmo sem correspondência.
- **CROSS JOIN**: Retorna o produto cartesiano entre as tabelas.

## Métodos e Comandos Usados nas Aulas

Durante as aulas, foram utilizados diversos comandos SQL para manipulação e consulta de dados em bancos relacionais. Entre os principais estão:

- **CREATE TABLE**: Criação de tabelas no banco de dados.
- **INSERT INTO**: Inserção de novos registros nas tabelas.
- **SELECT**: Consulta de dados armazenados nas tabelas.
- **UPDATE**: Atualização de dados existentes.
- **DELETE**: Remoção de registros.
- **ALTER TABLE**: Modificação da estrutura de uma tabela (adicionar/remover colunas, chaves, etc).
- **DROP TABLE**: Exclusão de uma tabela do banco de dados.
- **JOIN**: Combinação de dados de duas ou mais tabelas relacionadas.
- **CONSTRAINTS**: Definição de restrições como PRIMARY KEY, FOREIGN KEY, UNIQUE, NOT NULL, etc.
- **GROUP BY / HAVING**: Agrupamento e filtragem de resultados agregados.
- **Funções de agregação**: `SUM`, `AVG`, `COUNT`, entre outras.

Esses comandos são fundamentais para a criação, manutenção e consulta de bancos de dados relacionais.

## Palavras Reservadas em SQL

As **palavras reservadas** em SQL são termos que possuem função específica e não podem ser utilizados como identificadores sem tratamento especial. Elas definem comandos, operadores e estruturas essenciais para manipulação dos dados.

Exemplos de palavras reservadas:

- **FROM**: Indica a tabela de onde os dados serão selecionados.
- **WHERE**: Define condições para filtrar registros.
- **DEFAULT**: Define um valor padrão para uma coluna.
- **ORDER BY**: Ordena os resultados.
- **GROUP BY**: Agrupa registros com valores iguais.
- **HAVING**: Filtra grupos após o agrupamento.
- **DISTINCT**: Remove duplicidades.
- **VALUES**: Usado na inserção de dados.
- **IN, BETWEEN, LIKE**: Operadores de comparação.

### Operadores SQL

- **=** : Igualdade.  
- **<>** ou **!=** : Diferente.  
- **> / < / >= / <=** : Comparações numéricas.  
- **AND / OR / NOT** : Operadores lógicos.  
- **BETWEEN** : Intervalo.  
- **IN** : Lista de valores.  
- **LIKE** : Padrões em textos.  

## Resumo dos Aprendizados Recentes

- Bancos de dados relacionais organizam dados em **tabelas**.  
- **Chaves primárias** identificam registros de forma única.  
- **Cardinalidade** define quantas ocorrências de uma entidade podem se relacionar com outra.  
- **Normalização** reduz redundância e inconsistências.  
- **Subconsultas** permitem consultas aninhadas.  
- **JOINs** permitem combinar dados de várias tabelas de diferentes formas.  

---

## Autor

Projeto desenvolvido por **Haynner J. M. (HayJM)**
