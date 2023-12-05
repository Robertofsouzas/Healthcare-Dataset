# Healthcare-Dataset



# Visão geral

Este projeto tem como objetivo realizar uma análise detalhada de dados relacionados à área da saúde, abordando desde a obtenção dos dados até sua integração em diferentes ambientes de armazenamento e visualização.


## Ferramentas Utilizadas
- **Python**: Linguagem de programação versátil e poderosa.
- **Jupyter Notebook**: Ambiente interativo para execução e documentação do código.


### Etapas do Projeto
1. Baixando como Bibliotecas

Antes de começar, certifique-se de ter as bibliotecas necessárias instaladas. Utilize o seguinte comando para conectá-los:


- **import** os
- **import** pandas as pd
- **import** numpy as np
- **import** matplotlib.pyplot as plt
- **import** seaborn as sns
- **from** datetime import datetime
- **impor**t time
- **import** pymssql as sql
- **import** warnings
- **warnings.filterwarnings("ignore")**
- **import** pyodbc
- **import** sqlalchemy as sa 

### 2. Configurando as  Credenciais Kaggle

Para obter os dados, é necessário configurar as credenciais do Kaggle. Siga os passos abaixo:

Crie uma conta no Kaggle .
Faça login e vá para a seção "Conta".
Clique em “Create New API Token” para baixar o arquivo kaggle.json.
Mova o arquivo kaggle.jsonpara o diretório ~/.kaggle/no seu sistema.

### 3. Visualizando os Dados

Nesta etapa, o foco entenderá a estrutura inicial dos dados. Utilize o Jupyter Notebook ou qualquer IDE Python para explorar o conjunto de dados.

### 4. Análise Exploratória

Explore os dados mais a fundo, identificando padrões, distribuições e possíveis correlações. Utilize bibliotecas como matplotlibe seabornpara criar visualizações informativas.

### 5. Renomeando as Colunas

Realize uma renomeação de colunas para garantir consistência e clareza

### 6. Conversão de Tipos de Dados

Verifique e ajuste os tipos de dados conforme necessário.

### 7. Verificando Valores Ausentes

Identifique e trate valores ausentes.

### 8. Verificando valores discrepantes

Analise outliers para garantir a qualidade dos dados

### 9. Resumo Estatístico

Obtenha estatísticas descritivas para entender melhor a distribuição dos dados.

### 10. Carregando no SQL Server

Integre os dados em um ambiente SQL Server. Certifique-se de ter o SQL Server e o Python configurados corretamente. Utilize uma biblioteca pyodbce sqlalchemy.



### 11. Integração com Microsoft Fabric Power BI online e Data Warehouse

Desenvolva um dashboard interativo no Power BI, integrando dados provenientes do SQL Server e do Data Warehouse. -se de ter as credenciais e configurações.

Painel do Power BI:

Nome do Arquivo:Healthcare_Dashboard.pbix


![Dashboard Healthcare](https://private-user-images.githubusercontent.com/67076322/288103096-8308b657-f60e-43ca-b0b8-8070f8345688.jpeg?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTEiLCJleHAiOjE3MDE3OTE0NzYsIm5iZiI6MTcwMTc5MTE3NiwicGF0aCI6Ii82NzA3NjMyMi8yODgxMDMwOTYtODMwOGI2NTctZjYwZS00M2NhLWIwYjgtODA3MGY4MzQ1Njg4LmpwZWc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBSVdOSllBWDRDU1ZFSDUzQSUyRjIwMjMxMjA1JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDIzMTIwNVQxNTQ2MTZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0wZDkyMmFmYzI0NTBmZTI2YmU1Yjc5OWNjZDUzNTlmMWM2YjUwMmExNGU1OWUwM2YzMTYzYWZlYTg4ZmYxZGYyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.ho-LQrKtnW6rBkomuzRU3l-lFUYi-CULLNqUYzSFIDo)








