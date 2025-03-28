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
   ![Gráfico 1](path/to/your/image1.png)

2. **Gráfico 2: Correlação entre Temperatura Real e Aparente**
   ![Gráfico 2](path/to/your/image2.png)

3. **Gráfico 3: Variação da Umidade ao Longo dos Meses**
   ![Gráfico 3](path/to/your/image3.png)

### Etapa 2: Aplicação de Machine Learning
Na segunda etapa, aplicamos um modelo de **Machine Learning** para prever a temperatura com base em variáveis como umidade, velocidade do vento e condições climáticas. O modelo foi treinado e validado, alcançando um excelente desempenho.

- **Modelo utilizado**: [Inserir o modelo de Machine Learning utilizado, como Random Forest, Regressão Linear, etc.]
- **R² alcançado**: 91% (indica que o modelo explica 91% da variabilidade da temperatura, o que é considerado um excelente desempenho para esse tipo de tarefa).

## Conclusão
O modelo foi capaz de prever a temperatura com alta precisão, o que pode ser útil para futuras análises climáticas ou previsões. Além disso, a análise exploratória revelou informações valiosas sobre as variáveis climáticas e suas relações, fornecendo insights importantes sobre o clima da região de Szeged.

## Como rodar o código
Para rodar o código do projeto, siga os seguintes passos:

1. Clone o repositório:
   ```bash
   git clone https://github.com/andrewgabr/Analise_Clim-tica_Szeged-Regressao.git
