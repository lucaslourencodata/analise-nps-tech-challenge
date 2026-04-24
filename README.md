# 📊 Análise de NPS – Tech Challenge Fase 1

## 🎯 Objetivo
Este projeto tem como objetivo identificar os principais fatores operacionais que impactam a satisfação do cliente (NPS) em um cenário de e-commerce, além de propor formas de antecipar clientes com risco de insatisfação.

---

## 📁 Base de Dados
A base contém informações sobre:
- Pedidos (valor, quantidade de itens, pagamento)
- Logística (tempo de entrega, atraso)
- Atendimento (contatos, tempo de resolução)
- Indicadores de satisfação (CSAT e NPS)

---

## 🔍 Metodologia

### 1. Entendimento do Negócio
Análise do impacto da experiência do cliente no NPS e nos resultados do negócio.

### 2. Definição da Variável Alvo
Utilização do `nps_score`, categorizado em:
- Detrator (0–6)
- Neutro (7–8)
- Promotor (9–10)

### 3. Análise Exploratória (EDA)
Foram analisados fatores como:
- Atraso na entrega
- Contato com atendimento
- Tempo de resolução
- Reclamações

---

## 📊 Principais Insights

- Atrasos superiores a 2 dias aumentam a proporção de detratores de **62% para 93%**
- Existe um efeito cascata:
  **atraso → contato → reclamação → demora na resolução → insatisfação**
- A combinação de falhas operacionais tem impacto maior que fatores isolados

---

## 💡 Recomendações

- Reduzir atrasos superiores a 2 dias
- Monitorar clientes com múltiplos contatos
- Melhorar o tempo de resolução
- Atuar na causa raiz dos problemas

---

## 🤖 Modelo Preditivo (Proposta)
Sugere-se o uso de um modelo de classificação para prever clientes com maior probabilidade de se tornarem detratores.

---

## ▶️ Como Executar

1. Acessar o notebook em `notebooks/analise_nps.ipynb`
2. Fazer upload do arquivo CSV presente em `data/`
3. Executar as células para reproduzir a análise

---

## 📁 Estrutura do Projeto

- data/: base de dados utilizada
- notebooks/: análise exploratória em Python

---

## 📌 Conclusão

A análise demonstra que fatores operacionais impactam diretamente o NPS, sendo possível antecipar clientes insatisfeitos e agir de forma proativa na melhoria da experiência do cliente.
