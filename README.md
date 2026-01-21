# 📊 RFV Customer Segmentation

**RFV Customer Segmentation** é um aplicativo interativo desenvolvido em **Python e Streamlit** para análise e segmentação de clientes com base no modelo **Recência, Frequência e Valor (RFV)**.  

O sistema permite que empresas entendam melhor seus clientes, identifiquem padrões de compra e definam **ações de marketing personalizadas**.

---

## 🌐 Funcionalidades principais

### Upload e visualização de dados
- Importação de arquivos `.csv` contendo informações de compras.
- Visualização interativa dos primeiros registros.
- Informações básicas sobre a tabela (linhas, colunas, datas mínima e máxima de compras).

### Análise RFV
- **Recência (R)**: número de dias desde a última compra de cada cliente.
- **Frequência (F)**: quantidade de compras realizadas por cliente.
- **Valor (V)**: total gasto por cliente.
- Combinação em **tabela RFV completa**, com índice pelo ID do cliente.

### Classificação e pontuação
- Definição de **quartis** para R, F e V.
- Classificação de cada cliente com letras (`A` a `D`) com base nos quartis.
- Geração do **RFV Score** (ex: `AAA`, `DBC`, etc.) combinando R, F e V.

### Ações de marketing/CRM
- Mapeamento do RFV Score para **ações recomendadas de marketing**, como:
  - Enviar cupons de desconto.
  - Incentivar fidelização.
  - Recuperar clientes inativos.
  - Identificar clientes de baixo valor.

### Exportação
- Exportação da tabela final com classificações e ações de marketing para **Excel** (`RFV_Segmentacao.xlsx`).

---

## 🛠️ Tecnologias e Bibliotecas
- **Python 3.x**
- **Streamlit**: interface web interativa
- **Pandas**: manipulação e análise de dados
- **NumPy**: cálculos e operações numéricas
- **Datetime**: manipulação de datas

- use o csv no repositorio para teste.

https://rfv-3wde.onrender.com/

link de acesso.
