# Projeto Big Data com Dataset ENEM 2021

## Descrição do Projeto
Este projeto tem como objetivo a análise e processamento de dados do Exame Nacional do Ensino Médio (ENEM) 2021, utilizando ferramentas de Big Data e data science. Os dados foram extraídos do dataset disponibilizado pelo INEP e processados utilizando PySpark, pandas e PyMongo.

## Ferramentas e Tecnologias Utilizadas
Apache Spark com PySpark: Utilizado para processamento distribuído e análise de grandes volumes de dados.<br>
Pandas: Utilizado para manipulação e análise de dados em DataFrames.<br>
PyMongo: Utilizado para fazer a conexão com MongoDB e obter os dados.


## Projeto
O notebook pode ser encontrado em: 
https://colab.research.google.com/drive/1o7xevOZmiFK23izvPtxdqrzUbhEH4m2f?usp=sharing <br>
Ou direto neste <a href='https://github.com/Devrafael112/bigdata-enem/blob/main/big_data_apache_spark.ipynb'>repositório </a>

## Configuração do ambiente

### Instalando Dependências (Windows)
No terminal cole os comandos abaixo para a criação, ativação do ambiente virtual e instalação das dependências.
```
python -m venv venv && .\venv\Scripts\activate && pip install -r requirements.txt
```

### Instalando Dependências (Linux/Mac)
Criação e ativação do ambiente virtual
```
python3 -m venv .venv && source .venv/bin/activate && pip install -r requirements.txt
```
