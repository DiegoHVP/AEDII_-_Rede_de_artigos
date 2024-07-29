# Análise de Redes de Coautoria com Base em Artigos de Universidades

## Introdução
Este estudo tem como objetivo analisar redes de coautoria entre pesquisadores com base em suas afiliações. Utilizamos dados de publicações relacionadas a diferentes Objetivos de Desenvolvimento Sustentável (ODS) e construímos grafos onde os nós representam autores e as arestas representam coautorias entre autores que compartilham a mesma afiliação.

## Dados Utilizados
Os dados foram extraídos do site scopus em formato CSV contendo informações sobre os artigos de professores publicados na UFRN para quatro ODS:
- 04 (Educação de Qualidade)
- 05 (Igualdade de género)
- 11 (Cidades e Comunidades Sustentáveis)
- 12 (Consumo e Produção Responsáveis) 

## Montagem da Rede
Para cada ODS, montamos uma rede onde:
- Cada nó representa um autor.
- Arestas são criadas entre autores que compartilham pelo menos uma afiliação.

## Visualizações e Interpretações

### ODS 04: Educação de Qualidade

#### Grafo da Rede
![Grafo da Rede ODS 04](imagens/ods04_grafo.png)

#### Grau dos Nós vs Grau Médio dos Vizinhos
![Grau dos Nós vs Grau Médio dos Vizinhos ODS 04](imagens/ods04_grafico.png)

**Interpretação**:
A rede do ODS 04 mostra uma alta densidade de pontos na parte inferior esquerda o que sugere que muitos autores colaboram principalmente dentro de pequenos grupos ou com poucos outros autores.


### ODS 05: Igualdade de género

#### Grafo da Rede
![Grafo da Rede ODS 05](imagens/ods05_grafo.png)

#### Grau dos Nós vs Grau Médio dos Vizinhos
![Grau dos Nós vs Grau Médio dos Vizinhos ODS 05](imagens/ods05_grafico.png)

**Interpretação**:
A rede do ODS 05 tem poucos autores porém o padrão se mantém, os poucos autores quem tem um número um pouco maior de publicações sugere que colaboram principalmente dentro de pequenos grupos ou com poucos outros autores pois tem uma quatidade media de vizinhos semelhantes.

### ODS 11: Cidades e Comunidades Sustentáveis

#### Grafo da Rede
![Grafo da Rede ODS 11](imagens/ods11_grafo.png)

#### Grau dos Nós vs Grau Médio dos Vizinhos
![Grau dos Nós vs Grau Médio dos Vizinhos ODS 11](imagens/ods11_grafico.png)

**Interpretação**:
A rede do ODS 11 apresenta um número maior de nós em comparação com o ODS 04, porém seu comportamente e um pouco diferente, temos uma concentração maior de autores que tem poucos artigos com diferentes afiliações. Além disso, os pouco autores que tem muitas publicações tende a publicar com outros autores que tem muitas publicações.

### ODS 12: Consumo e Produção Responsáveis

#### Grafo da Rede
![Grafo da Rede ODS 12](imagens/ods12_grafo.png)

#### Grau dos Nós vs Grau Médio dos Vizinhos
![Grau dos Nós vs Grau Médio dos Vizinhos ODS 12](imagens/ods12_grafico.png)

**Interpretação**:
A rede do ODS 05 tem a estrutura é semelhante as outras. Ainda temos uma grande concentração de autores com pouco pubilicações porém agora temos alguns autores que com poucos artigos mais com conjunto de autores que tem muitas publicações com outras universidades.



## Conclusão
A análise das redes de coautoria nos ODS forneceu observações interessantes sobre as dinâmicas de colaboração entre pesquisadores da UFRN. Cada ODS apresenta características únicas que refletem as especificidades de cada área de pesquisa. Compreender essas estruturas pode ajudar a desenvolver estratégias para promover colaborações mais eficazes e aumentar o impacto das pesquisas realizadas.

