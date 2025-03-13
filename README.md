# projeto-ecommerce
DIO projeto-ecommerce
# Projeto Conceitual de Banco de Dados para E-commerce

Este projeto consiste na criação de um esquema conceitual para um banco de dados de e-commerce, utilizando o modelo Entidade-Relacionamento Estendido (EER). O objetivo é modelar as principais entidades e seus relacionamentos, com ênfase na correta especificação de chaves primárias (PK) e chaves estrangeiras (FK).

## Narrativa

O modelo abrange as seguintes entidades:

* **Cliente:** Clientes podem ser pessoas físicas (PF) ou jurídicas (PJ), com informações de identificação, contato e endereço.
* **Produto:** Produtos são vendidos por uma plataforma online, com informações de nome, descrição, preço e estoque.
* **Pedido:** Pedidos são criados por clientes e contêm informações de compra, endereço de entrega e status.
* **Pagamento:** Pedidos podem ter uma ou mais formas de pagamento associadas.
* **Entrega:** Pedidos possuem informações de entrega, como status e código de rastreio.

## Objetivos

* Modelar as entidades e seus relacionamentos de forma clara e concisa.
* Especificar corretamente as chaves primárias (PK) e chaves estrangeiras (FK).
* Utilizar conceitos do modelo EER para representar situações complexas, como herança e relacionamentos ternários.
* Criar um esquema que possa ser implementado em um SGBD relacional, como MySQL.

## Ferramentas

* MySQL Workbench ou DBDesigner (para criação do diagrama)
* GitHub (para versionamento e compartilhamento do projeto)

## Próximos Passos

* Implementar o esquema em um SGBD relacional.
* Adicionar restrições de integridade ao banco de dados.
* Criar consultas SQL para recuperar e manipular os dados.
* Desenvolver uma aplicação para interagir com o banco de dados.
