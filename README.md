# Redução de Dimensões (Dimensionality Reduction)

## Introdução

Este projeto demonstra como aplicar técnicas de redução de dimensionalidade, especificamente PCA (Análise de Componentes Principais) e t-SNE (t-distributed Stochastic Neighbor Embedding), em dois datasets diferentes. 

Embora a maioria dos modelos preditivos já escale os dados automaticamente, ao trabalhar com PCA, devemos realizar a escalonamento dos dados manualmente. 

## Exemplos

Este repositório contém três exemplos distintos de como trabalhar com PCA em dois datasets:

1. **PCA aplicado no dataset IRIS**
2. **PCA aplicado no dataset Digits**
3. **Redução de Dimensão no dataset Digits com t-SNE e PCA por Percentual de Integridade**

### Dataset IRIS

O dataset da planta Iris possui 4 características. Não é possível plotar os 4 elementos em um gráfico para visualização direta, pois isso requer 4 dimensões. A ideia do PCA é minimizar a quantidade de dimensões para que possamos visualizar os dados de forma mais simples e também melhorar a performance do nosso modelo em termos de tempo, sem perder a essência do dataframe.

### Dataset Digits

No dataset Digits, demonstramos a redução de dimensão utilizando tanto PCA quanto t-SNE. Além disso, aplicamos PCA considerando o percentual de integridade dos dados.

## Estrutura do Projeto

- `iris_pca.py`: Script que aplica PCA no dataset Iris.
- `digits_pca.py`: Script que aplica PCA no dataset Digits.
- `digits_tsne.py`: Script que aplica t-SNE no dataset Digits.
- `README.md`: Este arquivo que você está lendo.

## Como Executar

1. Clone este repositório:
   ```bash
   git clone https://github.com/adja-18/dimensionality-reduction
