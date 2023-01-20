# Prevendo a Evolução do COVID-19 no Brasil.

**Projeto:** Criando Modelos com Python e Machine Learning para Prever a Evolução do COVID-19 no Brasil.

**Promovido:** Geração Tech Unimed-BH - Ciência de Dados - Digital Innovation One.

**Autor**: Neylson Crepalde.

**Resumo**: O projeto tem como objetivo explorar e análisar os dados da Covid-19 no Brasil, no período inicial da pandemia. 

-------------------------------

## Descrição:

No primeiro momento tratamos e análisamos os dados usando a biblioteca [Pandas](https://pandas.pydata.org/)(tratamento de dados) e [Plotly](https://plotly.com/) (visualização de dados).
Com isso podemos gerar gráficos que nos oferecem informações a respeito do que queremos, como por exemplo este que mostra o número que casos confirmado em dado período:
  
 
![Casos_Confirmados_no_Brasil](https://user-images.githubusercontent.com/84606803/213818265-e8f607a0-ac21-422c-896f-f5c2961ec1bc.png)

---
Depois dos dados serem tratados e os explorados, passamos para próxima etapa. No caso, a predição de novos casos. Pra isso utilizamos [pmdARIMA](https://pypi.org/project/pmdarima/) e [Prophet](https://facebook.github.io/prophet/docs/quick_start.html).   
No exemplo abaixo utilizamos os dados que tinhamos dos primeiros meses de 2020 para prever como seria o andamento da pandemia ao decorrer do ano, este é o resulto:
  
 ![image](https://user-images.githubusercontent.com/84606803/213819517-8e186521-8aa8-435a-b33f-b66096117d1d.png)
  
