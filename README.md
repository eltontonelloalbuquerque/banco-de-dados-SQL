# Desafio de Modelagem de Banco de Dados para E-commerce

Este projeto visa modelar um banco de dados para um cenário de e-commerce, com foco na criação de queries SQL para realizar consultas mais complexas. A modelagem envolve tabelas relacionadas a clientes, pedidos, pagamentos, entregas, produtos, fornecedores e estoques.

## Modelo Lógico

O modelo lógico do banco de dados está composto pelas seguintes tabelas:

- **Cliente**: Contém informações sobre o cliente (Pessoa Física ou Jurídica).
- **Pedido**: Registra os pedidos realizados pelos clientes.
- **Pagamento**: Informações sobre os pagamentos realizados.
- **Entrega**: Dados sobre o status e código de rastreio das entregas.
- **Produto**: Informações sobre os produtos disponíveis para venda.
- **Fornecedor**: Contém informações sobre os fornecedores dos produtos.
- **Estoque**: Relaciona os produtos com seus respectivos fornecedores e a quantidade em estoque.

### Objetivos do Projeto

- Criar o esquema do banco de dados com as tabelas relacionadas.
- Implementar queries para responder a perguntas importantes, como:
  - Quantos pedidos foram feitos por cada cliente?
  - Relação de produtos, fornecedores e estoques.
  - Identificar se algum vendedor também é fornecedor.

### Como Rodar o Projeto

1. Crie um banco de dados no seu SGBD.
2. Execute o script de criação das tabelas e inserção de dados.
3. Execute as queries SQL para obter as informações desejadas.
