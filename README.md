# 👷 Projeto Poços Correlatos
## 1. 🗒️ Documentação
> Autor: Millena Thalyne <br>
Data: 27/12/2023 <br>
Linguagem de Programação: Python <br>
Banco de Dados: SQL Server <br>
> *OBS: Projeto proposto como desafio para vaga de Cientista de Dados na MStar Consulting.*
## 2. 📖 Objetivo Central
Este, consiste projeto consiste em encontrar poços correlatos, ou seja, poços que tenham características muito próximas uma das outras.
## 3. 📖 Descrição 
- Nesse desafio, deve-se criar um modelo de Machine Learning, utilizando a base de dados 'dados_pocos.csv' para, dado uma entrada (com características de um projeto de perfuração de poços) este algoritmo deve exibir uma lista de quatro poços correlatos a este;
- Além disso, esta base de dados deve ter uma conexão com um banco de dados relacional, responsável por trazê-lo para este ambiente de desenvolvimento.
### 3.1 🎲 Base de Dados
- A base de dados utilizada é a 'dados_pocos.csv' que apresenta uma série de características referentes a projetos de perfuração de poços;
Esses projetos são divididos em fases, além de separados por tipo (Vertical ou Horizontal);
- As demais variáveis presentes nesses dados, são:
Nome: Nome que identifica o projeto do poço
   - Fase: É o número da fase. Um projeto é dividido em fases.
   - Tipo Poço: Existem aqui 2 tipos de poços VERTICAL ou HORIZONTAL.
   - LDA (Lâmina D'Água): LDA é o valor em metros, que corresponde a distância entre a superfície do mar até o ponto de perfuração em poços subaquático.
   - Diâmetro Fase: Para cada fase da perfuração pode-se usar uma broca com diâmetro diferente. Aqui o diâmetro é descrito em polegadas.
   - Metragem: Valor em metros que corresponde ao total perfurado naquela fase.
   - NFases: Corresponde ao número total de fases que o projeto exigiu.
### 3.2 🎲 Banco de Dados
- O banco de dados utilizado foi o SQL Server, um dos bancos mais utilizados para quem precisa armazenar dados sem se preocupar com escalabilidade e velocidade de resgate destes (características visíveis em bancos de dados não-relacionais, muito utilizado em aplicações web, por exemplo);
- A escolha desse banco em especial se dá pela facilidade de configuração e conexão *host* local, atual situação durante criação deste projeto.
> *Para mais informações, visualizar notebook disponibilizado na pasta "Projeto Python".*
