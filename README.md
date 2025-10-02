Projeto Banco de Dados - Biblioteca


Este projeto consiste na modelagem de um Banco de Dados Relacional para gerenciar uma biblioteca, contemplando clientes, editoras, livros, pedidos e estoque.


🔹 Estrutura


Cliente → cadastro de pessoas físicas e jurídicas (com CPF, RG, CNPJ, IE).

Livros → armazenam informações como título, categoria, ISBN, autor e ano.

Pedidos → relacionam clientes com os livros adquiridos.

Editora → guarda dados de contato, valor e telefone das editoras.

Estoque → controle da quantidade disponível de cada livro.


A modelagem foi desenvolvida no MySQL Workbench, utilizando chaves primárias e estrangeiras para garantir integridade referencial.


Projeto Banco de Dados - Loja de Peças


Este projeto consiste na modelagem de um Banco de Dados Relacional para uma loja de peças, abrangendo clientes, fornecedores, vendas, compras e estoque.


🔹 Estrutura


Usuário / Pessoa → cadastro de clientes e funcionários, com dados pessoais e login de acesso.

Fornecedor → responsável pelo fornecimento das peças.

Peça → armazena informações sobre descrição, grupo e subgrupo.

Compra → registra aquisições feitas junto aos fornecedores.

Venda → armazena pedidos de clientes com seus respectivos itens.

Estoque → controla saldo, movimentações e quantidades disponíveis.


O modelo foi construído no MySQL Workbench, aplicando conceitos de normalização e integridade relacional.
