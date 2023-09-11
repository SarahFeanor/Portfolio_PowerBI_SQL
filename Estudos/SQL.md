[![capa](https://media.discordapp.net/attachments/1088554408469602305/1140761341506879508/Black_Technology_LinkedIn_Banner_6.jpg?width=1025&height=256)](https://github.com/SarahFeanor?tab=repositories)

<sub> 🔗 [LinkedIn](https://www.linkedin.com/in/sarahfrezende/) | [Medium](https://medium.com/@sarahfrezende) |  [Portfólio de Data Science](https://github.com/sarahfeanor/Portfolio-DataScience)
 | [Portfólio Power BI](https://github.com/SarahFeanor/Portfolio_PowerBI)

# 🔹 SQL

Visão geral dos principais comandos SQL e dar um exemplo básico para cada um deles:

## 🔶 **SELECT**:
   
   Usado para recuperar dados de uma ou mais tabelas.

   Exemplo:
   ```sql
   SELECT nome, idade FROM alunos WHERE idade > 18;
   ```

## 🔶 **INSERT** 

Adiciona novos registros a uma tabela.

   Exemplo:
   ```sql
   INSERT INTO produtos (nome, preço) VALUES ('Laptop', 1000);
   ```

## 🔶 **UPDATE** 

Atualiza registros existentes em uma tabela.

   Exemplo:
   ```sql
   UPDATE clientes SET cidade = 'Nova York' WHERE id = 123;
   ```

## 🔶 **DELETE**

Remove registros de uma tabela.

   Exemplo:
   ```sql
   DELETE FROM pedidos WHERE data < '2023-01-01';
   ```

## 🔶 **CREATE TABLE**

Cria uma nova tabela no banco de dados.

   Exemplo:
   ```sql
   CREATE TABLE funcionários (
       id INT PRIMARY KEY,
       nome VARCHAR(255),
       cargo VARCHAR(255)
   );
   ```

## 🔶 **ALTER TABLE**

Modifica a estrutura de uma tabela existente.

   Exemplo:
   ```sql
   ALTER TABLE clientes ADD COLUMN telefone VARCHAR(15);
   ```

## 🔶 **DROP TABLE**

Exclui uma tabela do banco de dados.

   Exemplo:
   ```sql
   DROP TABLE produtos;
   ```

## 🔶 **CREATE INDEX**

Cria um índice em uma ou mais colunas para melhorar o desempenho de consultas.

   Exemplo:
   ```sql
   CREATE INDEX idx_nome ON funcionários (nome);
   ```

## 🔶 **ALTER INDEX**

Modifica um índice existente.

   Exemplo:
   ```sql
   ALTER INDEX idx_nome RENAME TO idx_nome_sobrenome;
   ```

## 🔶 **GRANT**

Concede permissões a usuários para acessar objetos do banco de dados.

    Exemplo:
    ```sql
    GRANT SELECT, INSERT ON produtos TO usuário1;
    ```

## 🔶 **REVOKE**

Revoga permissões previamente concedidas a usuários.

    Exemplo:
    ```sql
    REVOKE INSERT ON produtos FROM usuário1;
    ```

## 🔶 **JOIN**

Combina dados de duas ou mais tabelas com base em uma condição específica.

    Exemplo:
    ```sql
    SELECT pedidos.id, clientes.nome
    FROM pedidos
    INNER JOIN clientes ON pedidos.cliente_id = clientes.id;
    ```

Esses são alguns dos comandos SQL mais comuns. Lembre-se de que o SQL é uma linguagem poderosa para gerenciar e consultar bancos de dados, 
e existem muitos outros comandos e recursos avançados disponíveis para atender às necessidades específicas de cada projeto.
