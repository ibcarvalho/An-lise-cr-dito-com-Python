# Analise-credito-com-Python

## Objetivo

Análise exploratória e preditiva de crédito bancário. Utilizando Python, Pandas, Seaborn, Matplotlib e Scikit-learn para prever o **score de crédito** de clientes.

---

## Fonte de Dados

Este projeto foi desenvolvido com uma base de dados sintética, criada para simular um ambiente real de negócio. O objetivo é demonstrar habilidades em análise de dados, tratamento, modelagem e geração de insights a partir de variáveis como profissão, comportamento de pagamento, mix de crédito e outros indicadores financeiros.

---

## Procedimentos

1. **Importação de Bibliotecas**:
   Carregamento das ferramentas essenciais para manipulação, visualização e modelagem de dados.

2. **Carregamento dos Dados**:
   Leitura dos arquivos CSV e verificação inicial do dataset (shape, tipos, valores nulos).

3. **Exploração Inicial**:
   Inspeção das colunas, estatísticas descritivas e tipos de dados.

4. **Limpeza e Transformação**:
   Remoção de colunas desnecessárias, codificação de variáveis categóricas com LabelEncoder e padronização do dataset.

5. **Análise Exploratória (EDA)**:
   Visualização de distribuições, correlações e padrões entre variáveis — com gráficos de barras, pizza, countplot e heatmap.

6. **Modelagem e Avaliação**:
   Treinamento e comparação de dois algoritmos (Random Forest e KNN), com análise por acurácia, classification report e matrizes de confusão.

7. **Geração de Insights**:
   Identificação das variáveis com maior influência no score de crédito por meio da importância de features do Random Forest.

8. **Previsão em Novos Clientes**:
   Aplicação do modelo treinado em dados inéditos para prever o score de cada novo cliente.

---

## Resultados

| Modelo | Acurácia |
|---|---|
| Random Forest | ~82% |
| KNN | ~74% |

**Melhor modelo:** Random Forest Classifier

As variáveis com maior impacto na previsão do score:

1. Comportamento de pagamento
2. Mix de crédito
3. Dívida pendente
4. Número de atrasos

---


## Tecnologias Utilizadas

| Biblioteca | Uso |
|---|---|
| `pandas` | Manipulação e análise de dados |
| `scikit-learn` | Modelagem, pré-processamento e avaliação |
| `matplotlib` | Visualizações estáticas |
| `seaborn` | Visualizações estatísticas |

---

## Licença

MIT License — sinta-se à vontade para usar e modificar.


