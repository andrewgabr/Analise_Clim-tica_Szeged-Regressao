# Análise Climática de Szeged, Hungria (2006-2016) com Machine Learning

Este projeto realiza uma análise climática dos dados coletados entre 2006 e 2016 na cidade de Szeged, Hungria. O objetivo é explorar as variáveis climáticas como temperatura, umidade, vento e visibilidade e, com base nessa análise, treinar um modelo de **Machine Learning** para prever a temperatura.

## Objetivos do Projeto

### Etapa 1: Análise Exploratória de Dados (EDA)
Na primeira etapa, foi realizada uma análise exploratória dos dados climáticos. Através de gráficos e estatísticas, investigamos as distribuições das variáveis climáticas e identificamos padrões sazonais, bem como relações entre variáveis. Os principais pontos investigados foram:

- **Distribuições das variáveis climáticas**: temperatura, umidade, velocidade do vento, visibilidade.
- **Padrões sazonais**: Como as variáveis variam ao longo dos meses e anos.
- **Correlação entre variáveis**: Investigação da correlação entre temperatura real e aparente, e a influência da velocidade do vento na visibilidade.

### Perguntas a serem respondidas
- Qual o tipo de clima mais comum em Szeged por ano entre 2006 e 2016?
- Existe uma correlação entre a temperatura real (`temperature`) e a temperatura aparente (`apparentTemperature`)?
- Como a umidade (`humidity`) varia ao longo dos meses do ano?

#### Gráficos da Etapa 1
Aqui estão alguns dos gráficos gerados para visualizar os dados:

1. **Gráfico 1: Distribuição da Temperatura Real e Aparente ao Longo do Ano**
   ![Gráfico 1](https://github.com/andrewgabr/Analise_Clim-tica_Szeged-Regressao/blob/main/imgs/1.png?raw=true)

2. **Gráfico 2: Correlação entre Temperatura Real e Aparente**
   ![Gráfico 2](https://github.com/andrewgabr/Analise_Clim-tica_Szeged-Regressao/blob/main/imgs/2.png?raw=true)

3. **Gráfico 3: Variação da Umidade ao Longo dos Meses**
   ![Gráfico 3](https://github.com/andrewgabr/Analise_Clim-tica_Szeged-Regressao/blob/main/imgs/3.png?raw=true)

### Etapa 2: Aplicação de Machine Learning
Na segunda etapa, aplicamos um modelo de **Machine Learning** para prever a temperatura com base em variáveis como umidade, velocidade do vento e condições climáticas. O modelo foi treinado e validado, alcançando um excelente desempenho.

- **Modelo utilizado**: Linear Regression / Random Forest
- **R² alcançado**: 91% (indica que o modelo explica 91% da variabilidade da temperatura)


