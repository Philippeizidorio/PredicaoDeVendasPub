# Prevendo Vendas Em Campanhas De Publicidade Online 🛒💲
![Alt ou título da imagem](https://github.com/user-attachments/assets/63b2f3e0-4c83-41ca-8242-842eb9c7ae45)

### ◾Contexto:
Um negócio local está investindo mensalmente em plataformas de publicidade online, como Youtube, Facebook e newspaper, para a prospecção de leads (pessoas interessadas em seus produtos). A fim de acompanhar o desempenho desses investimentos, a empresa registra todos os gastos com publicidade e todos os retornos de vendas gerados a partir desses investimentos.

Para **entender** melhor **a relação entre as variáveis** presentes nesses registros e **identificar os fatores que mais impactam** na geração de leads, a empresa solicitou uma análise dos dados. **Além disso, a empresa busca criar um modelo de predição** de valores para estimar o retorno de vendas que pode ser gerado a partir de um determinado investimento em publicidade.

### ◾Instalação das bibliotecas

Para desenvolvimento do projeto, foram utilizadas bibliotecas como **[pandas](https://pandas.pydata.org/)**, **[matplotlib](https://matplotlib.org/)**, **[scikit-learn](https://scikit-learn.org/)**, **[seaborn](https://seaborn.pydata.org/)** e **[plotly](https://plotly.com/python/)**

Para trazermos algumas bibliotecas necessárias na criação do projeto, foi necessário utilizar o comando **pip install** ou importá-las com o comando **import** em uma célula do Colab.

```
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
%pip install plotly
%pip install cufflinks
%pip install chart-studio
import chart_studio.plotly as py
import cufflinks as cf
import plotly.graph_objects as go
import plotly.express as px
from sklearn.linear_model import LinearRegression
```

### ◾Análise Exploratória De Dados(AED):
Após ter importado a base, trabalhamos no entendimento dos dados, realizamos verificações para possíveis tratamentos, análise da correlação e identificação de tendências usando técnicas estatísticas e bibliotecas como **Pandas**, **Seaborn**, **Matplotlib** e **Plotly**.

### ◾Dicionário Dos Dados:

`youtube`: Investimentos no youtube.

`facebook`: Investimentos no facebook.

`newspaper`: Investimentos em newspaper. 

`Sales`: Valor das vendas. **Variável target*

### ◾Correlação entre as variáveis com 'Price'(Pairplot):


<p align="center">
  <img src="https://github.com/user-attachments/assets/b48cf586-6c6d-4b1c-b87b-b30c4c29c97f" alt="Correlação Entre as Variáveis">
</p>

<p align="center">
</p>


### ◾Correlação entre as variáveis com 'Price'(Heatmap):


<p align="center">
  <img src="https://github.com/user-attachments/assets/dd7f4cbb-6b48-4e0a-a3b0-6d61bdd94c0c" alt="Correlação com heatmap">
</p>


### ◾Treinando e Testando o modelo de ML:
Nessa etapa final, separamos as variáveis ___'x'___ e ___'y'___, definimos as bases ___train___ e ___test___. Por fim, importamos a Regressão Linear do Sklearn para treinamento dos dados, predição e mensuração do R² Score.
<p align="center">
  <img src="https://github.com/user-attachments/assets/76b1ba08-97f3-41c1-bd54-3089d81deb2e" alt="Comparação entre y_test e y_pred">
</p>

<p align="center">
 Obtivemos um R²_Score de 88%(Alta linearidade)
</p>

### ◾Utilização:
Para usar este código, siga estas etapas:

1. Instale as bibliotecas(dependências) necessárias listadas logo no início;

2. Copie e cole o código em um ambiente Python, como Jupyter Notebook ou um script Python;

3. Execute o código para carregar o conjunto de dados, tratamentos, treinar os modelos e gerar métricas de desempenho e visualizações;

4. Insira os parâmetros desejados para realizar a previsão de preços dos imóveis.

### ◾ Tecnologias Utilizadas: 
<div <br> 
<img src="https://img.shields.io/badge/Python-4695dd?style=for-the-badge&logo=python&logoColor=FFD43B">
<img src="https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white">
<img src="https://img.shields.io/badge/Matplotlib-%232A9D8F.svg?style=for-the-badge&logo=Matplotlib&logoColor=black">
<img src="https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white">
</div> 

## Autor:

<img  src="https://github.com/Philippeizidorio/AnaliseTRIM_AgenciaMKTDIGITAL/assets/145637595/9800ac43-2070-48d4-9002-dbf82f756f2c" width="80" alt="cognitiveclass.ai logo" align="left" /> 

### &nbsp;&nbsp;Philippe Izidório

<p>
&nbsp;&nbsp;Estudante De Ciência De Dados / Business Intelligence / Analista De Dados<br/>
&nbsp;&nbsp;LinkedIn: https://www.linkedin.com/in/philippeizidorio/<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;E-mail: euphilippeizidorio@gmail.com<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Portifólio de projetos em Data Science: https://github.com/Philippeizidorio
</p>

