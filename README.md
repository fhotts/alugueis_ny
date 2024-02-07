# Análise exploratória e modelagem preditiva de preços de aluguel na cidade de Nova York
Este projeto consiste na análise exploratória e modelagem preditiva dos preços de aluguel de propriedades em Nova York. Uma empresa foi designada para trabalhar em colaboração com um cliente que está desenvolvendo uma plataforma de aluguéis temporários na cidade de Nova York. O objetivo principal é criar um modelo de previsão de preços com base nos dados fornecidos pelo maior concorrente do cliente. A análise exploratória dos dados fornecerá insights valiosos sobre padrões, tendências e características do mercado de aluguel em Nova York. Posteriormente, a equipe desenvolverá e avaliará modelos preditivos para determinar os preços de aluguel com base em diversas variáveis relevantes, como localização, tipo de propriedade e disponibilidade. O desempenho dos modelos será avaliado utilizando métricas adequadas para problemas de regressão.


## Instalação
Faça o download ou clone este repositório para o seu computador.
Instale as dependências necessárias executando pip install -r requirements.txt.

## Execução do Projeto
Abra o notebook Jupyter fornecido neste repositório no programa de sua preferência (Google Colab ou Jupyter Notebook).
Siga as instruções dentro do notebook para executar as análises estatísticas e EDA.

## Relatórios
Todas as análises estão incluídas dentro do notebook Jupyter fornecido neste repositório.

## Códigos de Modelagem
Todos os códigos de modelagem estão incluídos no notebook Jupyter fornecido neste repositório.

## Arquivo .pkl
O modelo treinado está disponível como um arquivo .pkl neste repositório. Você pode carregá-lo usando o seguinte código Python:

```python
import pickle

# Carregar o modelo a partir do arquivo .pkl
with open('gbr_aluguel_ny.pkl', 'rb') as file:
    modelo = pickle.load(file)
```
