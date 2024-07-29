# Análise de Redes de Coautoria entre Afiliações

Este projeto analisa detalhes das redes de coautoria entre afiliações em diferentes Objetivos de Desenvolvimento Sustentável (SDGs). Utilizando dados de coautoria, construímos grafos que representam as conexões entre autores que compartilham afiliações e calculamos várias métricas de rede.

## Uso

### 1. Estrutura dos Dados

Cada arquivo CSV deve conter as seguintes colunas:
- `Author(s) ID`: IDs dos autores, separados por `; `
- `Affiliations`: Afiliações dos autores, separadas por `; `


### 2. Interpretação dos Resultados

O script gera uma tabela com as seguintes métricas para cada rede SDG:
- **Qtd vértices**: Número de nós (autores) na rede.
- **Qtd arestas**: Número de arestas (conexões) na rede.
- **Coef. de grau da assortatividade**: Grau de assortatividade da rede.
- **Qtd Comp. Conectados**: Número de componentes conectados na rede.
- **Tamanho do Comp. Gigante (GCC)**: Tamanho do maior componente conectado.
- **Coef. de clustering avg_clustering()**: Coeficiente médio de clustering da rede.


## Análise do resultado

##### Quantidade de Vértices e Arestas:
- SDG04: 1227 vértices, 5278 arestas
- SDG05: 691 vértices, 3203 arestas
- SDG11: 1921 vértices, 39383 arestas
- SDG12: 1587 vértices, 29938 arestas

SDG11 tem a maior rede de coautoria, enquanto SDG05 tem a menor.

##### Coeficiente de Grau da Assortatividade:
- SDG04: 0.823674
- SDG05: 0.880578
- SDG11: 0.997610
- SDG12: 0.971542

SDG11 e SDG12 mostram forte tendência de autores de grau similar colaborarem entre si.


##### Quantidade de Componentes Conectados

- SDG04: 130
- SDG05: 76
- SDG11: 162
- SDG12: 139

SDG11 é a mais fragmentada, enquanto SDG05 é a mais coesa.

##### Tamanho do Componente Gigante (GCC)

- SDG04: 206
- SDG05: 89
- SDG11: 232
- SDG12: 301

SDG12 tem o maior componente gigante, indicando maior conectividade central.


##### Coeficiente de Clustering Médio

- SDG04: 0.870749
- SDG05: 0.908419
- SDG11: 0.914116
- SDG12: 0.918693

SDG12 e SDG11 têm a maior propensão para formar grupos fechados de coautoria.