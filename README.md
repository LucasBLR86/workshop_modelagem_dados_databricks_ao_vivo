# Workshop: Modelagem de Dados no Databricks (Ao Vivo)

Bem-vindo ao repositório do workshop de modelagem de dados no Databricks! Este material foi criado para um evento ao vivo, cobrindo os conceitos e práticas essenciais de modelagem de dados na plataforma Databricks.

## 📋 Sobre o Workshop

Este workshop apresenta, de forma prática, como modelar dados na plataforma Databricks, abordando:

- **Medalhão de Dados (Medallion Architecture)**: camadas Bronze, Silver e Gold
- **Modelagem dimensional**: tabelas de fatos e dimensões (star schema)
- **Slowly Changing Dimensions (SCD)**: Tipo 1 e Tipo 2
- **Delta Lake**: recursos de tabelas como time travel e mudanças de esquema
- **Unity Catalog**: governança e organização de catálogos, schemas e tabelas
- **Streaming Tables e Materialized Views**: Databricks SQL e Lakeflow

## 🎯 Objetivos de Aprendizagem

Ao final do workshop, você será capaz de:

1. Estruturar uma arquitetura de dados no padrão Medallion
2. Criar tabelas de fatos e dimensões com Databricks SQL
3. Implementar histórico de alterações em dimensões (SCD Tipo 2)
4. Usar o Unity Catalog para organizar e governar seus dados
5. Aplicar boas práticas de nomenclatura e documentação de tabelas

## 📁 Estrutura do Repositório

```
workshop_modelagem_dados_databricks_ao_vivo/
├── notebooks/
│   ├── 01_bronze_ingestao.sql      # Ingestão de dados na camada Bronze
│   ├── 02_silver_limpeza.sql       # Limpeza e padronização na camada Silver
│   ├── 03_gold_modelagem.sql       # Modelagem dimensional na camada Gold
│   └── 04_scd_tipo_2.sql           # Exemplo de SCD Tipo 2
└── README.md
```

## 🚀 Como Usar

1. **Importe o repositório** no seu workspace do Databricks (ou clone via Databricks Repos).
2. **Configure um SQL Warehouse** ou um cluster para executar os notebooks.
3. **Siga a ordem dos notebooks**: Bronze → Silver → Gold → SCD.
4. Execute as células SQL e observe a evolução dos dados em cada camada.

## 🛠️ Pré-requisitos

- Workspace do Databricks com acesso ao Databricks SQL
- Unity Catalog habilitado no workspace
- Permissões para criar schemas e tabelas em um catálogo

## 📊 Cenário de Exemplo

O workshop usa um cenário de vendas simplificado, com dados de:

- **Clientes** (dimensão)
- **Produtos** (dimensão)
- **Pedidos e Itens de Pedido** (fatos)

## 💬 Dúvidas e Contato

Em caso de dúvidas durante ou após o workshop, abra uma *issue* neste repositório ou entre em contato com o instrutor.

---

⭐ Se este material foi útil para você, deixe uma estrela no repositório!

