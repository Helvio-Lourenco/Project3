
# README para o Projeto 3 - DeOroAtelier Store (DOA Store)
DeOroAtelier Store (DOA Store)
Descrição do Projeto
Este projeto é uma aplicação de gestão para a loja de joias DeOroAtelier (DOA Store). O objetivo é desenvolver um sistema moderno utilizando Spring Boot e PostgreSQL para gerenciar funcionários, joias, clientes, pedidos e pagamentos. Esta aplicação segue as práticas recomendadas de design e implementação de software, incluindo uso de APIs RESTful, DTOs, e integrações com Swagger e, opcionalmente, Docker.

# Funcionalidades
# 1. Gestão de Funcionários
Cadastro de funcionários com identificadores únicos, NIF, nome, data de contratação e salário.
Diferenciação entre vendedores e gerentes com funcionalidade específica.
Implementação de herança para simplificar o código.
# 2. Gestão de Joias
Cadastro de joias com identificadores únicos, nome, tipo (colar, brinco, anel), material, peso, preço e quantidade em estoque.
Uso de interfaces e herança para diferenciar os tipos de joias.
Persistência das informações no banco de dados relacional.
# 3. Gestão de Clientes
Cadastro de clientes com NIF, email, telefone, endereço e identificadores únicos.
Associação de clientes com pedidos de compra.
# 4. Gestão de Pedidos
Criação de pedidos com cliente, data, lista de itens comprados e total da compra.
Atualização do estado dos pedidos (entregue, pendente, aceito, cancelado).
# 5. Gestão de Pagamentos
Registro de pagamentos com valor, data e método (cartão, transferência bancária, dinheiro).
Associação de múltiplos pagamentos a um pedido.

# Requisitos Técnicos
Banco de Dados: PostgreSQL para persistência dos dados.
Framework: Spring Boot para o backend.
Relacionamentos: Implementação de relações one-to-many, many-to-one e many-to-many.
APIs RESTful: CRUD completo com métodos HTTP adequados (GET, POST, PUT, DELETE).
DTOs: Transferência de dados entre o sistema e os consumidores das APIs.
Swagger: Documentação e teste das APIs.
Docker (Opcional): Implementação usando Docker para simplificar o setup do PostgreSQL e do Spring Boot.

# Estrutura do Projeto
O projeto segue as melhores práticas de modularização:

Entities: Classes que representam as tabelas do banco de dados.
Repositories: Interface para acesso e manipulação de dados.
Services: Contém a lógica de negócio.
Controllers: Endpoints RESTful para interação com o sistema.
DTOs: Classes para transferência de dados entre as camadas
