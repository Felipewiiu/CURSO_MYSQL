## Curso Mysql

*Comando para a criação de um DATABASE*

````
CREATE {DATABASE | SCHEMA} [IF NOT EXISTS] db_name
      [create_specification]

   create_specification:
            [DEFAULT] CHARACTER SET [=] charset_name
            [DEFAULT] COLLATE [=] collation_name
            DEFAULT ENCRYPTION [=] { 'Y' | 'N'}

````

## Comando para exclusão de tabela

````
DROP {DATABASE | SCHEMA} [IF EXISTS] db_name

````

1. Esse comando seleciona a tabela que deseja apagar e verifica se ela existe ou não.




