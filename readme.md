# Projeto Conceitual de E-commerce 🛒

Este repositório contém o esquema conceitual de um sistema de e-commerce, projetado para gerenciar produtos, estoques, vendas, clientes, pedidos, pagamentos e entregas.

## 📜 Descrição Geral

O objetivo deste projeto é criar uma base de dados eficiente para gerenciar as operações de um e-commerce. As principais funcionalidades incluem:
- **Cadastro de produtos** e controle de estoque.
- **Registro de vendas** realizadas pelos clientes.
- **Gestão de pedidos**, incluindo status de entrega e código de rastreamento.
- **Controle de clientes**, permitindo que sejam cadastrados como pessoas físicas (PF) ou jurídicas (PJ).
- **Gerenciamento de pagamentos** e rastreamento de status de entrega.

## 🗂 Estrutura do Esquema Conceitual

O diagrama ER abaixo representa o esquema conceitual projetado para o sistema:

- **Produto**: Registra os produtos disponíveis na loja.
- **Estoque**: Controla a quantidade de produtos disponíveis.
- **Venda de Produtos**: Registra as vendas realizadas, incluindo os produtos vendidos, o cliente que comprou e a data da venda.
- **Cliente**: Gerencia os dados dos clientes, sejam pessoas físicas (PF) ou jurídicas (PJ).
- **Pedido**: Controla os pedidos realizados, com informações sobre o status de entrega e código de rastreamento.
- **Fornecedor**: Cadastro dos fornecedores responsáveis pelo fornecimento dos produtos.
- **Pagamento**: Detalha os pagamentos realizados pelos clientes, especificando o tipo de pagamento e a data.

## 📊 Relacionamentos

- Um **produto** pode ter várias entradas no **estoque**.
- Um **produto** pode estar associado a várias **vendas**.
- Um **cliente** pode realizar várias **vendas** e **pedidos**.
- Um **cliente** pode ter vários **pagamentos** associados.
