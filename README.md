# POSTGRESQL 

## COMANDOS SHELL

- Lista os DB existentes na máquina
  ```
  \l
  ```

- Criação de um novo DB
  ```
  create data base nome_do_DB
  ```

- sair do DB
  ```
  \q
  ```

  - nome do meu DB 
  ```
  cursodb 
  ```

- mostra todas as tabelas presentes no DB
  ```
   \dt
  ```

  - criar tabela
  ```
   create table nome_da_tabela (
  ```

    - exemplo de tabela:
  ```
   create table alunos (
  id_aluno serial primary key,
  nome varchar(45),
  telefone varchar(15),
  );
  
  ```

  - inclusão de tabela no DB
  ```
   insert into nome_da_tabela (campos que ira atualizar, ex: (nome, telefone)) values (inserção de elementos no campo, ex: (DANIEL, 12345))
  ```

  - mostra todas as linhas cadastradas na tabela referente
  ```
   select * from nome_da_tabela
  ```
