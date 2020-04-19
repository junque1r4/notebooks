# Guia de referência para manipulação de dados

## O que é

Tutoriais curtos para servirem de referência básica a comandos e bibliotecas de Python.

## Como vai funcionar

Os tutoriais serão escritos em Notebooks Jupyter criada pelo Projeto Jupyter, os Notebooks ficarão na pasta [notes](https://github.com/junque1r4/notebooks/tree/master/notes) e os dados para análise e/ou teste ficarão na pasta [data](https://github.com/junque1r4/notebooks/tree/master/data).

## O que é Projeto Jupyter

O **Projeto Jupyter** é uma organização sem fins lucrativos criada para "desenvolver sofware de código aberto", padrões abertos e serviços para computação em dezenas de linguagens de programação. Via Wikipedia.

## O que é Jupyter Notebook

Um Notebook Jupyter é um ambiente computacional web para a internet rica para criação de documentos para a plataforma Jupyter. O termo "notebook" pode, dependendo do contexto, fazer referência a entidades distintas como Jupyter (aplicativo Web), Jupyter Python (servidor Web) ou ao formato de documento para a plataforma. Um documento Jupyter Notebook é estruturado formato JSON, contendo uma lista ordenada de células de entrada / saída que podem conter código, texto (usando Markdown), matemática, gráficos e texto enriquecido, geralmente terminando com a extensão ".ipynb".

## Como eu instalo o Jupyter Notebook

Plataformas GNU/Linux:

No terminal, via pip:

`$ pip3 install --upgrade pip`

`$ pip3 install jupyter`

Eu recomendo que você instale o gerenciador de pacotes anaconda, com ela o jupyter vem pré-instado.

Para usar o jupyter notebook:

`jupyter notebook`

Uma nova aba deve abrir no navegador.

obs: Caso tenha instalado o conda e não goste do **(base)** no seu terminal você pode tirar com o seguinte comando:

`conda config --set auto_activate_base false`

Isso irá retirar a inicialização automática do conda enviroment, sendo necessária a ativação manual:

`conda activate`

## To-do list do projeto

- [x] [Importação e exportação de dados com Pandas](https://github.com/junque1r4/notebooks/blob/master/notes/Pandas.ipynb)
- [ ] Usando Python para explorar seus datasets
- [ ] Plotando histogramas com NumPy, Matplotlib, Pandas & Seaborn
