# Análise de Vendas - Rede Tech

Script em Python para limpeza, processamento e análise do histórico de vendas de uma rede de lojas de tecnologia.

## 🛠️ Tecnologias Utilizadas
- **Python 3** (Pandas, NumPy, Matplotlib, Openpyxl)
- **Jupyter Notebook**

## 📂 Arquivos Necessários
- `vendas_tech.csv`: Base principal com o histórico de pedidos.
- `gerentes_lojas.xlsx`: Dados das filiais, gerentes e metas mensais.

## 🚀 Funcionalidades do Código
1. **Limpeza de Dados:** Tratamento de valores nulos, conversão de datas, remoção de duplicatas e padronização de textos.
2. **Novas Métricas:** Cálculo de **Faturamento** e categorização dos pedidos por **Forma de Venda** (Online/Presencial) e **Região**.
3. **Exploração e Filtros:** Criação de rankings de produtos mais vendidos e exportação de subconjuntos (ex: `Vendas_SP.csv`).
4. **Validação de Metas:** Cruzamento da base de vendas com a planilha de gerentes para atestar o atingimento de metas financeiras.
5. **Visualização:** Geração de curva de evolução do faturamento mensal.

## ⚙️ Como Executar
1. Instale as dependências: `pip install pandas numpy openpyxl matplotlib`
2. Coloque os dois arquivos de dados na mesma pasta do código.
3. Execute as células do Jupyter Notebook sequencialmente.
