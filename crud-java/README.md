# CRUD Java SE com MySQL
## CRUD em Java SE com MySQL, cadastro de usuário, usando JTable

Um aplicação básica usando o banco de dados MySQL, nela contém um CRUD usando JTables e outros componentes graficos do Swing toolkit em Java. No qual e feito pesquisa, inserção, atualização ao clicar em algum item da linha do JTable, e remover item.

```sql
create database db_usuario;

use db_usuario;

CREATE TABLE usuario (
id BIGINT(10) AUTO_INCREMENT,
nome VARCHAR(255),
cpf VARCHAR(255),
email VARCHAR(255),
telefone VARCHAR(255),
PRIMARY KEY (id)
);
```
