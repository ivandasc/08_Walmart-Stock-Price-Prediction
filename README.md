Previsão de Preços das Ações do Walmart
Descrição do Projeto
Neste projeto, realizamos uma análise de séries temporais para prever os preços futuros das ações do Walmart com base em dados históricos. Utilizamos técnicas de aprendizado de máquina, como ARIMA (AutoRegressive Integrated Moving Average) e métodos adicionais para análise, com o objetivo de identificar padrões e tendências ao longo do tempo e estimar preços futuros.

Objetivos
Análise Exploratória: Identificar padrões e tendências nos preços históricos das ações do Walmart.
Modelagem: Construir um modelo ARIMA para prever os preços futuros com base em dados históricos.
Avaliação: Medir a precisão do modelo usando métricas de erro como o RMSE (Root Mean Squared Error).
Visualização: Criar gráficos para visualizar dados históricos, previsões e análises.
Bibliotecas Utilizadas
pandas: Manipulação e análise de dados.
matplotlib: Visualização de dados.
seaborn: Gráficos estatísticos.
statsmodels: Modelagem de séries temporais com ARIMA.
sklearn: Métricas de avaliação de modelos.
gdown: Download de arquivos do Google Drive.
Instalação
Para executar este projeto, você precisará das seguintes bibliotecas Python. Você pode instalá-las usando pip:
pip install pandas matplotlib seaborn statsmodels scikit-learn gdown
Como Utilizar
Download dos Dados: O arquivo CSV contendo os dados históricos das ações do Walmart pode ser baixado diretamente do Google Drive.

URL do Google Drive: WMT.csv

Carregamento e Pré-processamento:

Carregue o arquivo CSV.
Converta a coluna 'Data' para o formato datetime.
Reamostre os dados para uma frequência diária.
Visualização:

Histograma dos preços de fechamento.
Gráfico de dispersão entre volume e preço de fechamento.
Gráfico de barras da média dos preços de fechamento por ano.
Modelagem e Previsão:

Treine um modelo ARIMA com os dados históricos.
Faça previsões para o conjunto de teste.
Avalie o modelo com métricas de erro, como RMSE.
Visualize os preços reais versus previstos.

Insights Adicionais
Tendência Geral: A análise dos gráficos mostra uma tendência de crescimento gradual, com períodos de queda moderada e estabilização com leves oscilações.
Dados Externos: Para uma análise mais completa, considere incluir dados macroeconômicos e notícias relevantes que possam impactar os preços das ações.
Licença
Este projeto está licenciado sob a MIT License.


