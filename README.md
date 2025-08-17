# 📊 AluraStore Brasil – Análise de Vendas

Este projeto realiza uma análise exploratória de dados (EDA) das lojas da **AluraStore**, avaliando o desempenho em termos de faturamento, vendas por categoria e outros indicadores importantes.

Os dados utilizados vêm de diferentes lojas (Loja 1 a Loja 4), fornecidos em arquivos CSV hospedados no GitHub.

---

## 📂 Estrutura do Projeto

- **AluraStoreBr.ipynb** → Notebook principal com todo o processo de análise e visualização.
- **Dados** → Os dados das lojas são carregados diretamente de URLs públicas (CSV).

---

## ⚙️ Tecnologias Utilizadas

- [Python 3](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/) – Manipulação e limpeza dos dados
- [Matplotlib](https://matplotlib.org/) – Criação de gráficos
- [Seaborn](https://seaborn.pydata.org/) – Visualizações estatísticas
- [NumPy](https://numpy.org/) – Cálculos numéricos

---

## 📈 Análises Realizadas

1. **Importação e consolidação dos dados** das 4 lojas.  
2. **Cálculo do faturamento total por loja** com visualização em gráfico de barras.  
3. **Distribuição das vendas por categoria de produto**.  
4. Comparações e insights sobre o desempenho de cada loja.  

---

## ▶️ Como Executar o Projeto

1. Clone este repositório:
   ```bash
   git clone https://github.com/seu-usuario/AluraStoreBr.git
   cd AluraStoreBr
   ```

2. Crie um ambiente virtual e instale as dependências:
   ```bash
   python -m venv venv
   source venv/bin/activate  # (Linux/Mac)
   venv\Scripts\activate     # (Windows)

   pip install -r requirements.txt
   ```

3. Abra o Jupyter Notebook:
   ```bash
   jupyter notebook AluraStoreBr.ipynb
   ```

---

## 📌 Próximos Passos / Possíveis Melhorias

- Consolidar os dados das lojas em um único DataFrame para facilitar comparações.  
- Criar dashboards interativos com Plotly ou Streamlit.  
- Realizar análises preditivas (ex.: previsão de faturamento).  

---

## 👨‍💻 Autor

Projeto desenvolvido como parte de estudos de **Ciência de Dados** e **Análise Exploratória**.
