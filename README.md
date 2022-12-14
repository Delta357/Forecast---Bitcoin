# Modelo forecast bitcoin

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/tterb/atomic-design-ui/blob/master/LICENSEs)
[![GPLv3 License](https://img.shields.io/badge/License-GPL%20v3-yellow.svg)](https://opensource.org/licenses/)
[![AGPL License](https://img.shields.io/badge/license-AGPL-blue.svg)](http://www.gnu.org/licenses/agpl-3.0)
[![author](https://img.shields.io/badge/author-RafaelGallo-red.svg)](https://github.com/RafaelGallo?tab=repositories) 
[![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-374/) 
[![](https://img.shields.io/badge/R-3.6.0-red.svg)](https://www.r-project.org/)
[![](https://img.shields.io/badge/ggplot2-white.svg)](https://ggplot2.tidyverse.org/)
[![](https://img.shields.io/badge/dplyr-blue.svg)](https://dplyr.tidyverse.org/)
[![](https://img.shields.io/badge/readr-green.svg)](https://readr.tidyverse.org/)
[![](https://img.shields.io/badge/ggvis-black.svg)](https://ggvis.tidyverse.org/)
[![](https://img.shields.io/badge/Shiny-red.svg)](https://shiny.tidyverse.org/)
[![](https://img.shields.io/badge/plotly-green.svg)](https://plotly.com/)
[![](https://img.shields.io/badge/XGBoost-red.svg)](https://xgboost.readthedocs.io/en/stable/#)
[![](https://img.shields.io/badge/Tensorflow-orange.svg)](https://powerbi.microsoft.com/pt-br/)
[![](https://img.shields.io/badge/Keras-red.svg)](https://powerbi.microsoft.com/pt-br/)
[![](https://img.shields.io/badge/CUDA-gree.svg)](https://powerbi.microsoft.com/pt-br/)
[![](https://img.shields.io/badge/Caret-orange.svg)](https://caret.tidyverse.org/)
[![](https://img.shields.io/badge/Pandas-blue.svg)](https://pandas.pydata.org/) 
[![](https://img.shields.io/badge/Matplotlib-blue.svg)](https://matplotlib.org/)
[![](https://img.shields.io/badge/Seaborn-green.svg)](https://seaborn.pydata.org/)
[![](https://img.shields.io/badge/Matplotlib-orange.svg)](https://scikit-learn.org/stable/) 
[![](https://img.shields.io/badge/Scikit_Learn-green.svg)](https://scikit-learn.org/stable/)
[![](https://img.shields.io/badge/Numpy-white.svg)](https://numpy.org/)
[![](https://img.shields.io/badge/PowerBI-red.svg)](https://powerbi.microsoft.com/pt-br/)

Nesse projeto de forecast modelo previs??o bitcoin utlizando modelos ARIMA, SARIMA, SARIMAX como vai est?? o valor do bitcoin no futuro uma previs??o. 
Algumas ferramentas vai ser utilizada python autoarima, statsmodels, fbprophet.

No segundo projeto modelo processamento de linguagem natural an??lise de sentimentos e extra????o de t??picos, utlizando modelo LDA para fazer extra????o dos textos mais comentados.

Bases de dados foi extraida site do kaggle, e uma API em python extra????o dos dados.


![Logo](https://img.freepik.com/fotos-gratis/fundo-azul-da-tecnologia-do-grafico-do-mercado-de-acoes_53876-124650.jpg?w=1380&t=st=1661115158~exp=1661115758~hmac=25e7f89b88a5a4ee4e2e25be218a3548418dd4623bf2999136bb453fa2e754ef)


## Autores

- [@RafaelGallo](https://www.github.com/RafaelGallo)


## Stack utilizada

**Machine learning:** Python, R, autoarima, statsmodels, fbprophet



## Instala????o


Instala????o das bibliotecas para esse projeto no python.

```bash
  conda install -c conda-forge pandas 
  conda install -c conda-forge scikitlearn
  conda install -c conda-forge numpy
  conda install -c conda-forge scipy
  conda install -c conda-forge matplotlib
  conda install -c conda-forge statsmodels
  conda install -c conda-forge fbprophet
  conda install -c conda-forge pmdarima

  python==3.6.4
  numpy==1.13.3
  scipy==1.0.0
  matplotlib==2.1.2
  statsmodels==0.13.2
  fbprophet==0.7.1
  pmdarima==2.0.0



```
Instala????o do Python ?? altamente recomend??vel usar o anaconda para instalar o python. Clique aqui para ir para a p??gina de download do Anaconda https://www.anaconda.com/download. Certifique-se de baixar a vers??o Python 3.6. Se voc?? estiver em uma m??quina Windows: Abra o execut??vel ap??s a conclus??o do download e siga as instru????es. 

Assim que a instala????o for conclu??da, abra o prompt do Anaconda no menu iniciar. Isso abrir?? um terminal com o python ativado. Se voc?? estiver em uma m??quina Linux: Abra um terminal e navegue at?? o diret??rio onde o Anaconda foi baixado. 
Altere a permiss??o para o arquivo baixado para que ele possa ser executado. Portanto, se o nome do arquivo baixado for Anaconda3-5.1.0-Linux-x86_64.sh, use o seguinte comando: chmod a x Anaconda3-5.1.0-Linux-x86_64.sh.

Agora execute o script de instala????o usando.


Depois de instalar o python, crie um novo ambiente python com todos os requisitos usando o seguinte comando

```bash
conda env create -f environment.yml
```
Ap??s a configura????o do novo ambiente, ative-o usando (windows)
```bash
activate "Nome do projeto"
```
ou se voc?? estiver em uma m??quina Linux
```bash
source "Nome do projeto" 
```
Agora que temos nosso ambiente Python todo configurado, podemos come??ar a trabalhar nas atribui????es. Para fazer isso, navegue at?? o diret??rio onde as atribui????es foram instaladas e inicie o notebook jupyter a partir do terminal usando o comando
```bash
jupyter notebook
```


## Descri????o projetos

| Nome do projeto               | Link                                                |
| ----------------- | ---------------------------------------------------------------- |
| Bitcoin - S??rie temporal | [Link projeto](https://www.kaggle.com/datasets/varpit94/bitcoin-data-updated-till-26jun2021)|
| Bitcoin Tweets - NLP | [Link projeto](https://www.kaggle.com/datasets/kaushiksuresh147/bitcoin-tweets)|
| API Tweets - NLP | [Link projeto]()|
| API Bitcoin - S??rie temporal | [Link projeto]()|

## Screenshots

![App Screenshot](https://raw.githubusercontent.com/steffmul/nextbike/master/forecast.gif)


## Roadmap

- Previs??o dos bitcoin e a tendencia da moeda, modelo an??lise de sentimento o que pessoal est?? dizendo sobe as moedas.

- Extra????o de t??picos em textos, os sentimentos que as pessoas est??o dizendo.

- Verificar a t??ndencia dos textos.


## Feedback

Se voc?? tiver algum feedback, por favor nos deixe saber por meio de rafaelhenriquegallo@gmail.com

