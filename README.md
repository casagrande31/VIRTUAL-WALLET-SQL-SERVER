# VIRTUAL-WALLET-SQL-SERVER
# 💰 Carteira Virtual — Banco de Dados SQL

## 📌 Sobre o projeto

Este projeto consiste no desenvolvimento de um banco de dados para uma aplicação de **carteira virtual de criptomoedas**, desenvolvido como atividade acadêmica.

O objetivo é estruturar e organizar informações de clientes, moedas, carteiras digitais, corretoras e pares de moedas, permitindo o armazenamento e a consulta de dados relacionados às operações de uma carteira virtual.

O projeto foi desenvolvido utilizando SQL Server, aplicando conceitos de modelagem de dados, relacionamentos entre tabelas, integridade referencial, consultas SQL, índices, funções e views.

## 🛠️ Tecnologias utilizadas

- **SQL Server** — Sistema de gerenciamento de banco de dados.
- **SQL (T-SQL)** — Criação, manipulação e consulta de dados.
- **SQL Server Management Studio (SSMS)** — Ambiente utilizado para executar e gerenciar os scripts SQL.

## 🗄️ Estrutura do banco de dados

O banco de dados utilizado no projeto é `ESTUDO_DIRIGIDO`, organizado por meio do schema `WALLET`.

As principais tabelas são:

| Tabela | Descrição |
|---|---|
| `CLIENTE` | Armazena os dados dos clientes cadastrados. |
| `MOEDA` | Mantém os registros das moedas disponíveis no sistema. |
| `PARES_MOEDAS` | Armazena informações sobre pares de moedas e suas cotações. |
| `CORRETORA` | Organiza os dados das corretoras. |
| `CARTEIRA` | Representa as carteiras vinculadas aos clientes. |
| `ITEM_CARTEIRA` | Registra as moedas e respectivas quantidades presentes em cada carteira. |

## ⚙️ Funcionalidades e conceitos aplicados

- Criação e organização do banco de dados e do schema `WALLET`.
- Criação de tabelas com chaves primárias e estrangeiras.
- Definição de relacionamentos e integridade referencial.
- Criação de índices para auxiliar no desempenho das consultas.
- Inserção de dados para testes e demonstrações.
- Consultas SQL utilizando `SELECT`.
- Consulta de saldos e quantidades de moedas nas carteiras.
- Criação de views para facilitar a consulta de informações consolidadas.
- Desenvolvimento de funções SQL para cálculos e consultas relacionados aos valores das moedas.
- Elaboração de script para desfazer as alterações realizadas no banco de dados (*rollback*).

## 🚀 Como executar o projeto

### Pré-requisitos

- SQL Server instalado e em execução.
- SQL Server Management Studio (SSMS) ou ferramenta compatível para executar scripts T-SQL.

### Passo a passo

1. Clone este repositório ou faça o download dos arquivos.
2. Abra o SQL Server Management Studio.
3. Conecte-se à instância do SQL Server.
4. Abra o arquivo SQL principal do projeto.
5. Execute os scripts na ordem definida no trabalho, respeitando as dependências entre os objetos.

**Ordem recomendada de execução:**

1. Criação do banco de dados.
2. Criação do schema `WALLET`.
3. Criação das tabelas.
4. Criação dos índices.
5. Inserção dos dados de exemplo.
6. Execução das consultas SQL.
7. Criação e utilização das views e funções.

> **Atenção:** execute o script de rollback somente quando desejar desfazer as alterações previstas por ele. Verifique seu conteúdo antes da execução, pois ele pode remover objetos ou dados do banco.

## 🎯 Objetivo acadêmico

O projeto tem como finalidade aplicar, na prática, conhecimentos de banco de dados relacionais, incluindo modelagem, criação de estruturas, manipulação de dados, consultas, relacionamentos, funções e otimização básica de consultas.

## 👨‍💻 Autor

**Vítor Augusto Casagrande**

Estudante da área de Tecnologia da Informação, com interesse em desenvolvimento de software, banco de dados e automação.

