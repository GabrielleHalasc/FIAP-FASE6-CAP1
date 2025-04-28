# Visão Computacional com YOLO - FarmTech Solutions

## Descrição do Projeto
Este projeto tem como objetivo demonstrar a implementação de um sistema de visão computacional utilizando o modelo YOLO (You Only Look Once), com foco na identificação e classificação de objetos em imagens. O modelo foi treinado para identificar dois tipos de objetos, baseando-se em um dataset com imagens de dois objetos distintos.

### Objetivo
Criar um sistema de visão computacional com YOLO, aplicando-o em um cenário prático de monitoramento e reconhecimento de objetos em imagens. O sistema será utilizado pela FarmTech Solutions para mostrar o potencial da IA nas áreas de segurança patrimonial e saúde animal.

Metas da Entrega 1
1. Organização do Dataset
O dataset foi composto por:

- Objeto A: 40 imagens (32 para treinamento, 4 para validação, 4 para teste)

- Objeto B: 40 imagens (32 para treinamento, 4 para validação, 4 para teste)

As imagens foram armazenadas no Google Drive e rotuladas utilizando o site Make Sense IA.

2. Treinamento, Validação e Teste
O treinamento foi feito utilizando a YOLO adaptável, conforme explicado no capítulo 3 de Redes Neurais. O modelo foi treinado com diferentes números de épocas, e os resultados de desempenho foram avaliados.

3. Comparação de Resultados
Foram realizadas duas simulações com diferentes quantidades de épocas (30 e 60), e os resultados de acurácia, erro e desempenho foram comparados.

## Resultados

### Treinamento com 30 Épocas

Precisão média (P): 60%

Recall médio (R): 71.7%

mAP@50: 62.4%

### Treinamento com 60 Épocas
Precisão média (P): 69.5%

Recall médio (R): 74.5%

mAP@50: 66.7%

mAP@50-95: 54.4%

## Conclusões
O aumento no número de épocas resultou em uma melhoria no desempenho do modelo, principalmente na precisão e no recall.

O trator teve um melhor desempenho no treinamento de 60 épocas.

Mais experimentos são necessários para otimizar ainda mais o modelo, com mais dados e ajustes finos.

## Como Executar
Acesse o Colab: [Link para o Colab](https://colab.research.google.com/drive/1y22k3MkTvneE5HXThwCmYyoxhwPpPqtV#scrollTo=-thgTXw_hwZL)

Execute o código: O código está organizado em células. Basta seguir o passo a passo para treinamento, validação e teste.

Resultados: Os resultados de cada simulação podem ser encontrados nas pastas de saída (yolov5/runs/detect/expX), onde X é o número da simulação.



