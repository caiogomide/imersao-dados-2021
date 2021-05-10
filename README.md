## Introdução
Projeto desenvolvido na **Imersão Dados** de 2021, envolvendo o trabalho de **Data Science** aplicado na área de **Drug Discovery**, neste repositório estão apresentados os conteúdos das aulas e minhas resoluções dos desafios propostos.Esse projeto da Alura foi inspirado em um desafio do [Laboratory innovation science at Harvard](https://lish.harvard.edu/), no qual os dados foram disponibilizados em uma competição no [kaggle](https://www.kaggle.com/c/lish-moa). O desafio proposto por Harvard tinha como objetivo avançar o desenvolvimento de novas drogas  por meio da melhoria de algoritimos de predição de Mecanismos de Ação ativados por compostos químicos específico, este desafio foi explorado pela **Alura** na **Aula 5** desta imersão.

## Estrutura dos dados

Neste sentido, a base de dados apresentada nessa **Imersão Dados** pela **Alura**, os quais explorei nos desafios e no [Projeto Final](https://github.com/caiogomide/imersao-dados-desafio-final), fornecem informações sobre **23814** experimentos, como:

* Identificação do tratamento;
* Tipo de tratamento;
* Tempo de exposição ao tratamento;
* Tipo de dose do tratamento;
* Composto utilizado no tratamento;
* Expressões gênicas;
* Viabilidade celular.

Também foram analisados os principais dados dos resultados dos experimentos:

* Mecanismos de Ação analisados;
* Mecanismos de Ação ativados pelos experimentos.


## Estrutura das aulas e desafios propostos
### Aula 1 - Análise de dados, python, pandas e novos fármacos

#### Desafios Propostos:
- [x] 1. Investigar o motivo de a classe **tratamento** ser tão desbalanceada
- [x] 2. Plotar as **5 últimas linhas** da tabela de dados
- [x] 3. Calcular a proporção da classe **tratamento**
- [x] 4. Quantos **tipos de drogas** foram investigados?
- [x] 5. Pesquisar na **documentação** como utilizar método **Query**(Pandas)
- [x] 6. **Renomear colunas** de genes, retirando hifens
- [x] 7. **Estilizar** os gráficos utilizando o **matplotlib.pyplot**
- [x] 8. **Resumir** o que você aprendeu com estes **dados**
---
### Aula 2 - Estatísticas, visualização de dados e distribuições
#### Desafios Propostos:
- [x] 1. **Ordenar** os dados do gráfico countplot
- [x] 2. Melhorar a **visualização** dos dados
- [x] 3. Plotar histogramas utilizando o **SeaBorn**
- [x] 4. Refletir sobre a **manipulação dos tamanhos** das visualizações
- [x] 5. Plotar **box-plots e Histogramas** relevantes para analisar os dados
- [x] 6. **Resumir** o que você aprendeu com estes **dados**
---
### Aula 3 - Correlações, causalidade e relações entre genes
#### Desafios Propostos:
- [x] 1. Produzir as **Tabelas de Frequências 3.1** utilizando o método **groupby** do Pandas
- [x] 2. Produzir as **Tabelas de Frequências 3.1** com normalização entre **colunas**
- [x] 3. Explorar os valores que o parâmetro **aggfunc** recebe e testar utilizando as **Tabelas de Frequências 3.1**
- [x] 4. Explorar o método **melt** do Pandas e suas funcionalidades
- [x] 5. Calcular e analisar **correlações** entre as **expressões gênicas** e os **tipos celulares**
- [x] 6. Estudar como plotar uma matriz de correlação **(heatmap)**
- [x] 7. **Resumir** o que você aprendeu com estes **dados**
---
### Aula 4 - Merge de dados e análise de resultados
#### Desafios Propostos:
- [x] 1. Encontrar as **ações mais ativadas** pelos compostos químicos 
- [x] 2. Criar uma **coluna** denominada controle que indica se o experimento é **controle** ou não utilizando valores **booleanos**
- [x] 3. Criar colunas **24H**,  **48H**, **72H** que indicam se aquele experimento foi testado em alguma dessas horas, utilizando valores booleanos
- [x] 4. Estudar **documentação**, fazer **resumo** e utilizar métodos de unir **dataframes**, como o **merge**
- [x] 5. Fazer análise mais detalhada, considerando **tempo** e **doses** para comparar a **distribuição** **4.7**
- [x] 6. Analisar se há compostos que dependendo das **configurações do experimento**, como doses (D1/D2) e tempo (24/48/72), **não ativam certos mecanismos**
- [x] 7. Analisar se há compostos que dependendo das **configurações do experimento**, como doses (D1/D2) e tempo (24/48/72), **ativam mais mecanismos**
- [x] 8. Análisar se há compostos que dependendo das **configurações do experimento**, como doses (D1/D2) e tempo (24/48/72), **ativam mecanismos diferentes**
- [x] 9. **Resumir** o que você aprendeu com estes **dados**
---
### Aula 5 - Machine Learning, Sci-kit learning e desafios envolvidos
#### Desafios Propostos:
- [x] 1. **Teste** outros **modelos** de predição
- [x] 2. **Teste** outros parâmetros dos **modelos de predição** apresentados na aula, visando aumentar o **grau de acurácia**
- [x] 3. Estudar a **documentação** do Sklearn
- [x] 4. Estudar o fluxograma **"Choosing the best estimator"** do scikit learn
- [x] 5. Testar os **modelos de predição** com **variações** nas perguntas feitas
- [x] 6. Criar **modelo de predição** para descobrir se um experimento foi feito **com droga** ou **com controle**
- [x] 7. Criar **modelo de predição** para descobrir se um experimento foi feito **com droga** ou **com controle**, apenas para a droga mais utilizada
- [x] 8. **Resumir** o que você aprendeu com os dados
---

## Considerações finais
Finalmente, gostaria de agradecer aos instrutores: [Guilherme Silveira](https://www.linkedin.com/in/guilhermeazevedosilveira/), [Vanessa Leiko](https://www.linkedin.com/in/vanessa%2Dleiko%2Doikawa%2Dcardoso) e [Thiago Gonçalves](https://www.linkedin.com/in/thiago-gon%C3%A7alves-santos/) pela oportunidade de aprendizado entregada nessa imersão.

