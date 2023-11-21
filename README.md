## Entenda o Projeto

Este projeto utiliza JDBC no padrão Dao (Data Access Object). O DAO fornece métodos para realizar operações CRUD (Create, Read, Update, Delete) no banco de dados, incluindo inserção de novos registros, recuperação de dados, atualização de registros existentes e exclusão de informações.

Aqui trata-se de um projeto relacionado a vendedores e departamentos. A classe Seller armazena informações sobre o vendedor, como nome, email, data de nascimento e salário base. Já a classe SellerDao é responsável pela persistência e acesso aos dados dos vendedores no banco de dados.

O padrão DAO separa a lógica de negócios (representada pela classe Seller) da lógica de acesso aos dados (representada pela classe SellerDAO). O SellerDAO possui métodos para inserir, atualizar, excluir e buscar vendedores no banco de dados.

A classe Department contém um identificador e um nome, representando o ID e o nome do departamento, respectivamente. DepartmentDao e SellerDao possuem funções semelhantes, atuando em entidades diferentes. Ambas as classes são responsáveis pela manipulação dos dados relacionados às entidades (Seller e Department) em um banco de dados. Elas implementam operações como inserção, atualização, exclusão, busca por ID e listagem.

## Tecnologias Utilizadas

- JDBC
- SQL
- DAO

