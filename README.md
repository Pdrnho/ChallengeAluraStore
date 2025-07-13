# 🛍️ Análise de Desempenho das Lojas – Alura Store

Este projeto tem como objetivo analisar dados de quatro lojas da **Alura Store** para recomendar qual unidade deve ser vendida, com base em desempenho de vendas, avaliações de clientes, logística e popularidade de produtos.

---

## 📁 Estrutura do Projeto

- `AluraStoreBr.ipynb` – Notebook principal com todas as etapas do projeto:
  - Coleta e organização dos dados
  - Limpeza e padronização
  - Análise exploratória com gráficos
  - Geração de insights e recomendação final
- `README.md` – Documento explicativo do projeto
- `/imagens/` – Pasta com os gráficos gerados:
  - `faturamento_total.png`  
  - `avaliacao_lojas.png`  
  - `categorias_produtos.png`

---

## 🎯 Objetivo

Ajudar o proprietário da rede a tomar uma decisão estratégica sobre qual loja vender, considerando:

- Faturamento total  
- Avaliação média dos clientes  
- Produtos mais e menos vendidos  
- Categorias de venda com melhor e pior desempenho  
- Frete médio por loja  

---

## 📊 Etapas do Projeto

### 1. Coleta e tratamento dos dados
- Importação dos dados CSV de cada loja
- Unificação e padronização dos campos
- Conversão de colunas numéricas e textuais

### 2. Análise exploratória
- Comparação do faturamento total por loja  
  <img width="917" height="547" alt="Faturamento total por loja" src="https://github.com/user-attachments/assets/44faf2a3-85bb-40b5-aeee-6e290fb0b654" />

- Avaliação média das lojas  
  <img width="866" height="548" alt="Média de avaliação das lojas" src="https://github.com/user-attachments/assets/cc4f866d-78e2-4ce8-924c-5c94bffa4c15" />

- Distribuição das categorias de produtos mais vendidas  
  <img width="783" height="658" alt="Produtos vendidos por categoria" src="https://github.com/user-attachments/assets/7888c8ac-978e-4219-b6ab-5c61d0a8ab34" />

- Identificação dos produtos com maior e menor saída  
- Cálculo do frete médio por loja

### 3. Geração de insights
- Loja 1 teve o maior faturamento, mas a pior avaliação média e frete mais caro  
- Loja 3 foi a mais bem avaliada pelos clientes  
- Loja 4 teve o pior desempenho geral (menor faturamento, produtos de nicho e baixa avaliação)

---

## 🧠 Conclusões e Recomendação

A **Loja 4** foi recomendada para venda por apresentar os seguintes pontos fracos:

- Menor faturamento entre todas  
- Produtos com baixa rotatividade (ex: violão, guitarra)  
- Pior desempenho em categorias-chave como móveis e eletrônicos  
