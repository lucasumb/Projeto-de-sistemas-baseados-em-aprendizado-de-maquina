Este repositório contém o Projeto 1 para a disciplina de **Projeto de sistemas baseados em aprendizado de máquina**. O objetivo principal deste projeto é desenvolver um sistema de Machine Learning capaz de prever o preço de diárias de imóveis listados no Airbnb na cidade do Rio de Janeiro

---

## Objetivos

Melhorar os resultados obtidos em um problema de regressão (inside-airbnb)
1. Melhorar o EDA e seleção/criação de features;
2. Diferentes formas de normalização (e.g: min-max);
3. Modificação do algoritmo de otimização (e.g: adam, nadam, etc);
4. Outras estratégias que acharem pertinente mas mantendo o foco na regressão (e.g: LR diferentes, regularização, etc).

### Estrutura do Dataset

As features selecionadas para o modelo final foram:
* **accommodates**: Número de hóspedes que a propriedade acomoda.
* **bathrooms**: Número de banheiros.
* **bedrooms**: Número de quartos.
* **beds**: Número de camas.
* **price**: Preço da diária (variável alvo).

E incluindo:
* **price_per_accommodates**: Preço pelo tamanho da acomodação (price/accommodates).

---

## Como Executar o Projeto

Para executar a análise contida neste notebook, siga os passos abaixo:

**1. Pré-requisitos:**
-   Python 3.x
-   Jupyter Notebook ou Google Colab

**2. Dependências:**
As principais bibliotecas utilizadas são:
-   `pandas`
-   `numpy`
-   `torch`
-   `matplotlib`
-   `seaborn`
-   `scikit-learn`
-   `lazypredict` (utilizada para exploração de modelos, embora o código final esteja comentado).

---