Este projeto vale 10,0 pontos para a Unidade 3.
O trabalho final consiste na exploração aprofundada do Capítulo 6 – “Deep Learning with PyTorch”, do livro Deep Learning with PyTorch Step-by-Step.

# Participantes deste projeto

● IGOR SERGIO DE FRANCA CORREIA 

● LUCAS DE OLIVEIRA UMBELINO

---

## Objetivos

Código e experimentos devem ser feitos utilizando o MESMO DATASET escolhido na Unidade 2 da disciplina. Falamos com o professor e tivemos a permissão para alterar o dataset do MNIST para o FashionMNIST. A nota técnica (Medium ou Substack) deve abordar, com profundidade teórica, aplicações práticas e visualizações, os tópicos abaixo, todos aplicados ao dataset:


1. EWMA Meets Gradients

Explique como EWMAs (Exponentially Weighted Moving Averages) atuam para:

● suavizar variações bruscas de gradientes,

● permitir atualizações mais estáveis,

● servir de base para otimizadores adaptativos.

A explicação deve conter:

● Intuição de janelas equivalentes,

● α, β e períodos efetivos,

● Comparações com médias móveis simples,

● Gráficos reais aplicados ao dataset da Unidade 2.

2. Adam

Explique e demonstre na prática:

● como o Adam combina momentum + escalonamento por gradientes ao quadrado;

● o papel de β₁, β₂ e ϵ;

● comportamento do Adam no dataset escolhido.

Inclua:

● curva de perda,

● curvas de gradientes,

● comparação com SGD.

3. Visualizing Adapted Gradients

Gerar visualizações obrigatórias mostrando:

● gradientes crus,

● gradientes suavizados (EWMA),

● gradientes adaptados pelo Adam.

4. SGD e Suas Variantes

Explicar e demonstrar com gráficos:

● SGD simples,

● SGD com Momentum,

● SGD com Nesterov.

Mostrar intuitivamente:

● a “trajetória” da otimização,

● diferenças de estabilidade,

● velocidade de convergência.

5. Learning Rate Schedulers

A nota técnica deve conter:

● explicação teórica,

● exemplos em código,

● visualização da evolução da learning rate,

● comparação de desempenho entre diferentes schedulers.

Obrigatório incluir pelo menos dois entre:

● StepLR

● MultiStepLR

● ReduceLROnPlateau

● CyclicLR

● LambdaLR

---

## Como Executar o Projeto

Para executar a análise contida no [notebook](https://github.com/lucasumb/Projeto-de-sistemas-baseados-em-aprendizado-de-maquina/tree/main/Projeto3/notebooks), siga os passos abaixo:

**1. Pré-requisitos:**
-   Python 3.x
-   Jupyter Notebook ou Google Colab

**2. Dependências:**
As principais bibliotecas utilizadas são:
-   `torch`
-   `torchvision`
-   `matplotlib`
-   `numpy`
-   `pandas`
-   `pillow`
-   `requests`
-   `ipykernel`


---

### Postagem do Medium

* [link](https://medium.com/@igor.sergio.017/otimização-em-deep-learning-um-mergulho-prático-com-pytorch-e-fashionmnist-c2d57e991b66?postPublishedType=initial) 