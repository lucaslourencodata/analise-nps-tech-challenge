# 📊 Análise de NPS – Tech Challenge Fase 1

## 🚨 Principal Insight
Atrasos superiores a 2 dias aumentam drasticamente a insatisfação do cliente, elevando a proporção de detratores de **62% para 93%**.

---

## 🎯 Objetivo
Identificar os fatores que levam à insatisfação do cliente e permitir que a empresa atue de forma preventiva, reduzindo detratores e melhorando a experiência do cliente.

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

- Atrasos superiores a 2 dias aumentam significativamente a proporção de detratores
- Existe um efeito cascata na experiência do cliente:
  
  **atraso → contato → reclamação → demora na resolução → insatisfação**
  
- A combinação de falhas operacionais tem impacto maior do que fatores isolados

---

## 💡 Recomendações

- Priorizar pedidos com atraso superior a 2 dias
- Criar alertas para clientes com múltiplos contatos
- Reduzir o tempo de resolução para evitar escalonamento da insatisfação
- Atuar na causa raiz das falhas operacionais

---

## 🤖 Modelo Preditivo (Proposta)
Sugere-se o uso de um modelo de classificação para prever clientes com maior probabilidade de se tornarem detratores, permitindo atuação preventiva antes da aplicação do NPS.

---

## 📁 Estrutura do Projeto

- `data/`: base de dados utilizada  
- `notebooks/`: análise exploratória em Python  

---

## 📌 Conclusão

A insatisfação do cliente não ocorre de forma isolada, mas como resultado da combinação de falhas operacionais ao longo da jornada.  
Antecipar esses fatores permite que a empresa deixe de reagir ao problema e passe a atuar de forma preventiva, gerando vantagem competitiva.
