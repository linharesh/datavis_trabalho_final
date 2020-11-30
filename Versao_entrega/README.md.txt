# Instruções para executar o sistema

Para executar o sistema interativo de visualização é necessário ter um ambiente computacional com a linguagem **Python** na **versão 3.7.1 ou superior**. 

O projeto possui algumas dependências de softwares que precisam estar instaladas. As dependências são: 
1. numpy 1.15.4
2. pandas 0.23.3
3. plotly 4.12.0
4. ipywidgets 7.4.2. 
Sugerimos que a instalação das dependências seja feita utilizando a ferramenta pip.

Após instalar as dependências, o usuário precisa baixar os dados. Para executar o sistema de visualização, é necessário que o usuário tenha o arquivo de dados pré-processados chamado “preprocessed_data.csv”. Existem duas formas de obter esse arquivo.

A forma mais simples é baixar o arquivo diretamente por uma URL aberta pela plataforma Google Drive. Basta acessar a URL: https://drive.google.com/file/d/1pB1eCikVpC2yQk3uS5rfogu1-s-alLb6/view?usp=sharing, baixar o arquivo “preprocessed_data.csv” e colocar esse arquivo no diretório raiz deste projeto, e executar os notebooks de análise.

A outra forma de obter o arquivo “preprocessed_data.csv” é baixando os dados do Portal Brasileiro de Dados Abertos, através da URL:  https://dados.gov.br/dataset/microdados-do-exame-nacional-do-ensino-medio-enem. Então, o usuário deve extrair o arquivo compactado e colocar o arquivo "MICRODADOS_ENEM_2019.csv" no diretório raiz deste projeto, e executar o notebook "Pre-processamento.ipynb". A execução deste notebook irá produzir o arquivo “preprocessed_data.csv”. Uma vez que este arquivo for produzido, os notebooks de análise podem ser executados.

Os notebooks de análises são: “Caracterizacao.ipynb”, “Desempenho.ipynb” e “Presenca.ipynb”. Os notebooks podem ser abertos e executados pelo Jupyter Notebook.
