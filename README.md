# Análise do Setor de Limpeza e sua Relação com a Contratação de Pessoas

## 📊 **Visão Geral**
Este projeto busca analisar a evolução do setor de limpeza em relação à contratação de pessoal, especialmente com o uso de tecnologias que impactam processos operacionais. A análise explora como o crescimento de empresas de limpeza não necessariamente leva a um aumento proporcional no número de contratações de pessoas. Para isso, utilizamos técnicas de séries temporais e modelos preditivos, como ARIMA e SARIMA, para entender os padrões de contratação ao longo dos anos.

## 🔍 **Objetivo**
O objetivo principal desta análise é demonstrar que, apesar do crescimento das empresas no setor de limpeza, a adoção de novas tecnologias pode reduzir a necessidade de aumento de contratações. Isso é evidenciado através de dados históricos sobre o número de trabalhadores e a performance do setor.

## ⚙️ **Ferramentas e Técnicas Utilizadas**
- **Python**: Linguagem de programação utilizada para análise de dados.
- **Pandas**: Manipulação e preparação dos dados.
- **Matplotlib/Seaborn**: Visualização dos dados e gráficos.
- **Statsmodels (ARIMA/SARIMA)**: Modelagem preditiva de séries temporais para entender as tendências do setor.
- **ADF Test**: Teste de Dickey-Fuller aumentado para verificar a estacionariedade dos dados.

## 🔨 **Passos da Análise**
1. **Coleta de Dados**: Os dados foram obtidos a partir de fontes de dados públicas, como o CEMPRE.
2. **Tratamento dos Dados**: O processo envolveu a limpeza dos dados, transformando as colunas e ajustando os tipos de dados para análise.
3. **Análise Exploratória**: Foram feitas visualizações para entender os padrões nos dados históricos de contratações e o impacto das tecnologias.
4. **Modelagem Preditiva**: Utilizamos modelos ARIMA e SARIMA para prever as tendências de contratação no futuro.
5. **Conclusões**: A partir das previsões e da análise, foi possível concluir que o aumento das empresas não leva a um aumento diretamente proporcional na contratação de pessoas, especialmente devido à adoção de tecnologias que otimizam os processos.

## 📈 **Resultados**
As previsões feitas pelos modelos ARIMA e SARIMA mostraram que, apesar da tendência de crescimento no número de empresas, a necessidade de novas contratações se estabiliza ou até diminui em alguns casos, devido ao uso crescente de tecnologia no setor.

### Exemplos de Gráficos

1. **Gráfico de Séries Temporais**: Mostrando a evolução do número de contratações ao longo dos anos.
2. **Previsões Futuros**: Exibindo as previsões baseadas nos modelos de séries temporais.

## 🛠️ **Como Recriar a Análise**
Para recriar esta análise, siga os passos abaixo:

1. **Instalar as Dependências**:
    - `pip install pandas matplotlib seaborn statsmodels`
  
2. **Obter os Dados**:
    - Baixe os dados do CEMPRE ou fontes similares.

3. **Executar os Scripts**:
    - Importe os dados, faça o pré-processamento e execute os modelos ARIMA e SARIMA.

4. **Interpretar os Resultados**:
    - Use os gráficos e as previsões para entender as tendências.

## 📢 **Postagem no Linkedin**
A postagem será uma explicação detalhada sobre a análise, com foco em como a tecnologia tem impactado o setor de limpeza e como isso pode ser observado nas tendências de contratação. A postagem também incluirá exemplos dos gráficos e uma explicação sobre os modelos preditivos usados.

## 📑 **Conclusões**
- **Impacto da Tecnologia**: A adoção de novas tecnologias pode reduzir a necessidade de mais contratações, mesmo com o aumento do número de empresas no setor.
- **Séries Temporais**: Modelos como ARIMA e SARIMA ajudam a prever futuras tendências, fornecendo insights valiosos para a tomada de decisões estratégicas no setor.

## 🤝 **Contribuições**
Se você gostaria de contribuir com este projeto ou compartilhar suas próprias análises, sinta-se à vontade para abrir uma "issue" ou enviar um "pull request".
