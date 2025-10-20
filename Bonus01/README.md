Este desafio vale 2,5 pontos extras para a Unidade 1.
Devemos projetar e experimentar um problema de classificação binária usando conjuntos de dados gerados pelo sklearn e explorar como o ruído de dados, as funções de perda e as métricas de avaliação afetam o desempenho do modelo e os limites de decisão.

---

## Objetivos

1. Dataset: Generated using sklearn (with varying noise levels)
2. Explorar como o ruído de dados, as funções de perda e as métricas de avaliação afetam o desempenho do modelo e os limites de decisão.
3. Modificação do algoritmo de otimização (e.g: adam, nadam, etc);
4. Outras estratégias que acharem pertinente mas mantendo o foco na regressão (e.g: LR diferentes, regularização, etc).

1. Conjunto de dados: Gerado usando sklearn (com níveis de ruído variados)
2. Modelo: Regressão logística usando PyTorch
3. Arquitetura: Usou a classe `Architecture` fornecida
4. Funções de Perda: Comparação `BCELoss` e `BCEWithLogitsLoss`
5. Métricas: Exatidão, Precisão, Recall, F1, Matriz de Confusão
6. Parcelas: Limites de decisão e visuais de matriz de confusão
7. Repositório: Bem estruturado com README claro
8. Vídeo: Até 10 min explicando o projeto completo

---

## Como Executar o Projeto

Para executar a análise contida no [notebook](https://github.com/lucasumb/Projeto-de-sistemas-baseados-em-aprendizado-de-maquina/blob/main/Bonus01/notebooks), siga os passos abaixo:

**1. Pré-requisitos:**
-   Python 3.x
-   Jupyter Notebook ou Google Colab

**2. Dependências:**
As principais bibliotecas utilizadas são:
-   `numpy`
-   `torch`
-   `matplotlib`
-   `scikit-learn`

---

## Resultados

Com o `make_classification` que gera um conjunto de dados sintético para problemas de classificação mais simples, podemos fazer nossa primeira analise utilizando o modelo de regressão linear. Nesse caso, por ser um conjuntos de dados mais simples, não houve uma dificuldade elevada para traçar uma curva para os pontos, ao qual tivemos no total de 60 pontos dos dados de validação o resultado de:

* TN = 28, FN = 2, FP = 0, TP = 30, TPR = 1.0, FPR = 0, Acurácia = 0.97, Recall = 0.9375 e Precisão = 1.0

Com o `make_circles` que gera um conjunto de dados em formato de circulos, utilizando o modelo de regressão linear. Nesse caso, por ser um conjuntos de dados mais complexo para o modelo de regressão linear, houve bastante dificuldade para traçar uma curva para os pontos, ao qual tivemos no total de 60 pontos dos dados de validação o resultado de:

* TN = 11, FN = 9, FP = 20, TP = 20, TPR = 0.6897, FPR = 0.6452, Acurácia = 0.52, Recall = 0.6896 e Precisão = 0.5

Com o `make_moons` que gera um conjunto de dados em formato de luas, utilizando o modelo de regressão linear. Nesse caso, não foi tão complexo para traçar a curva dos pontos comparado ao caso do `make_circles`, mas foi mais dificil se comparada ao `make_classification`, ao qual tivemos no total de 60 pontos dos dados de validação o resultado de:

* TN = 28, FN = 2, FP = 3, TP = 27, TPR = 0.931, FPR = 0.097, Acurácia = 0.917, Recall = 0.931 e Precisão = 0.9

### Video explicativo

* [Parte 01](https://www.loom.com/share/5a22f95637f443439da6166d7e4e19d7?sid=6cafcb58-cb90-4316-8d1d-73f15478a2a4)
* [Parte 02](https://www.loom.com/share/c84095b2efb4459c929c630078c4bd7f?sid=e17ba9d8-9aa5-4544-a75e-cc36b64b743b)
