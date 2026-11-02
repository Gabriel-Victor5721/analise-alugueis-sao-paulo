# Análise Exploratória do Mercado de Aluguel Residencial em São Paulo

## 1. Identificação

**Candidato:** Gabriel Victor Ferreira da Silva

**Matrícula:** 01731662

**Curso:** Ciência da Computação

**Projeto:** Desafio SYNAPTA — Análise de preços de aluguel em São Paulo.

## 2. Objetivo do projeto

Este projeto tem como objetivo realizar uma análise exploratória de dados sobre anúncios de imóveis para aluguel na cidade de São Paulo.

A análise busca identificar padrões nos preços anunciados, observar diferenças entre localidades e investigar possíveis relações entre o valor do aluguel e características dos imóveis, como área e quantidade de quartos.

Também são avaliadas a qualidade dos dados e as limitações das informações disponíveis.

## 3. Fonte dos dados

O conjunto de dados utilizado foi obtido por meio do Kaggle:

[São Paulo Housing Prices — Kaggle](https://www.kaggle.com/datasets/renatosn/sao-paulo-housing-prices)

O arquivo principal utilizado na análise é `data.csv`, disponibilizado no formato CSV.

O dataset não foi incluído neste repositório. Para utilizar a análise, é necessário baixá-lo diretamente da fonte original, respeitando suas condições de uso.

## 4. Descrição das variáveis

A base utilizada possui 11.657 registros e 8 colunas:

| Coluna | Descrição |
|---|---|
| address | Endereço do imóvel |
| district | Localidade ou distrito do imóvel |
| area | Área do imóvel |
| bedrooms | Quantidade de quartos |
| garage | Quantidade de vagas de garagem |
| type | Tipo do imóvel |
| rent | Valor anunciado do aluguel |
| total | Valor total informado na base |

## 5. Ferramentas e tecnologias

- Python
- Google Colab
- Pandas
- Matplotlib

## 6. Etapas da análise

O desenvolvimento foi dividido nas seguintes etapas:

1. Importação e exploração dos dados.
2. Verificação da qualidade da base, incluindo valores ausentes, duplicidades e inconsistências.
3. Análise estatística dos valores de aluguel.
4. Comparação dos preços entre localidades.
5. Investigação da relação entre aluguel, área e quantidade de quartos.
6. Construção de visualizações gráficas.
7. Interpretação dos resultados e elaboração das conclusões.

## 7. Principais resultados

A análise apresentou os seguintes resultados:

- Quantidade de registros: 11.657 imóveis.
- Quantidade de variáveis: 8.
- Aluguel médio: R$ 3.250,81.
- Aluguel mediano: R$ 2.415,00.
- Correlação de Pearson entre área e aluguel: aproximadamente 0,667.

Os resultados indicam uma associação positiva entre a área dos imóveis e os valores anunciados de aluguel. Também foram observadas diferenças relevantes entre as localidades analisadas.

Foram desenvolvidos quatro gráficos para visualizar a distribuição dos preços, comparar localidades, investigar a relação entre área e aluguel e analisar os valores médios conforme a quantidade de quartos.

## 8. Conclusões

A análise permitiu observar que:

- A média dos aluguéis é superior à mediana, indicando influência de imóveis com preços mais elevados na distribuição.
- Existem diferenças expressivas entre os preços médios das localidades analisadas.
- A área apresenta associação positiva com o valor anunciado do aluguel.
- Imóveis com maior quantidade de quartos tendem a apresentar valores médios de aluguel mais elevados.
- A localização e as características dos imóveis são aspectos relevantes para compreender as diferenças de preços observadas.

## 9. Limitações da análise

Os resultados devem ser interpretados considerando algumas limitações:

- Os valores representam preços anunciados, que podem ser diferentes dos valores efetivamente negociados.
- A quantidade de anúncios varia entre as localidades.
- A base não apresenta todas as características que podem influenciar o preço de um imóvel.
- Foram identificados dois registros com área igual a zero, que não foram utilizados na análise de correlação entre área e aluguel.
- Algumas categorias possuem poucos registros, o que pode reduzir a representatividade de suas médias.
- Os resultados representam apenas o conjunto de anúncios analisado, não necessariamente todo o mercado imobiliário de São Paulo.

## 10. Como executar o projeto

1. Acesse o dataset no [Kaggle](https://www.kaggle.com/datasets/renatosn/sao-paulo-housing-prices).
2. Baixe o arquivo CSV principal, `data.csv`.
3. Abra o notebook disponibilizado neste repositório utilizando o Google Colab ou Jupyter Notebook.
4. Execute as células na ordem apresentada.
5. Quando solicitado, envie o arquivo `data.csv` para o ambiente do Google Colab.

### Dependências

As principais bibliotecas utilizadas são Pandas e Matplotlib. Consulte o arquivo `requirements.txt` para a relação de dependências do projeto.

## 11. Declaração de uso de inteligência artificial

Durante o desenvolvimento deste projeto, foi utilizada a ferramenta ChatGPT como apoio para esclarecimento de conceitos, orientação na organização da análise, revisão de textos e identificação de possíveis melhorias.

Os resultados numéricos, tabelas, gráficos e interpretações foram conferidos com base nas execuções do notebook e nos dados utilizados. As decisões e conclusões finais foram revisadas pelo candidato.

## 12. Arquivo principal

O arquivo principal deste projeto é o notebook `analise_alugueis_sao_paulo.ipynb`, que contém os códigos, as análises, as visualizações e as interpretações desenvolvidas.
