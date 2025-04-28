# FIAP - Faculdade de Informática e Administração Paulista

<p align="center">
<a href= "https://www.fiap.com.br/"><img src="assets/logo-fiap.png" alt="FIAP - Faculdade de Informática e Admnistração Paulista" border="0" width=40% height=40%></a>
</p>

<br>

# FIAP Fase6_Enterprise_Challenge_Sprint2


## 👨‍🎓 Integrantes: 
- <a href="https://www.linkedin.com/in/amanda-fragnan-b61537255/" target="_blank">Amanda Fragnan RM 555684 </a>
- <a href="https://www.linkedin.com/in/cunhaandre/" target="_blank">Andre Cunha RM 560648</a>
- <a href="https://www.linkedin.com/in/gabriellehalasc/" target="_blank">Gabrielle Halasc RM 560147</a> 

## 👩‍🏫 Professores:
### Tutor(a)
- <a href="https://www.linkedin.com/in/lucas-gomes-moreira-15a8452a/">Lucas Gomes Moreira</a>
### Coordenador(a)
- <a href="https://www.linkedin.com/in/profandregodoi/">André Godoi</a>

## 📜 Descrição

Projeto: Despertar da rede neural, Visao Computacional

🎯 Objetivo Geral 

Este projeto tem como objetivo demonstrar a implementação de um sistema de visão computacional utilizando o modelo YOLO (You Only Look Once), com foco na identificação e classificação de objetos em imagens. O modelo foi treinado para identificar dois tipos de objetos, baseando-se em um dataset com imagens de dois objetos distintos.
Criar um sistema de visão computacional com YOLO, aplicando-o em um cenário prático de monitoramento e reconhecimento de objetos em imagens. O sistema será utilizado pela FarmTech Solutions para mostrar o potencial da IA nas áreas de segurança patrimonial e saúde animal.

## 📊 Documentação do Processo de Preparação dos Dados

1. Organização do Dataset
O dataset foi composto por:

- Objeto A: 40 imagens (32 para treinamento, 4 para validação, 4 para teste)

- Objeto B: 40 imagens (32 para treinamento, 4 para validação, 4 para teste)

As imagens foram armazenadas no Google Drive e rotuladas utilizando o site Make Sense IA.
*Dados coletados no Google e armazenados no Colab*

2. Treinamento, Validação e Teste
O treinamento foi feito utilizando a YOLO adaptável, conforme explicado no capítulo 3 de Redes Neurais. O modelo foi treinado com diferentes números de épocas, e os resultados de desempenho foram avaliados.

3. Comparação de Resultados
Foram realizadas duas simulações com diferentes quantidades de épocas (30 e 60), e os resultados de acurácia, erro e desempenho foram comparados.


## 🧠 Resultados e Analise

### Treinamento com 30 Épocas

Precisão média (P): 60%

Recall médio (R): 71.7%

mAP@50: 62.4%

### Treinamento com 60 Épocas
Precisão média (P): 69.5%

Recall médio (R): 74.5%

mAP@50: 66.7%

mAP@50-95: 54.4%

### Conclusão:
1. Melhor Desempenho nas 60 Épocas:
Precision e Recall: O modelo alcançou melhores valores de precisão e recall após 60 épocas, tanto para o trator quanto para a casa, em comparação com 40 épocas. Isso indica que o modelo ficou mais preciso e capaz de identificar corretamente os objetos.

mAP50: A média de precisão nas imagens (mAP@50) aumentou, o que significa que a qualidade das detecções melhorou nas 60 épocas.

mAP50-95: O mAP@50-95, que é uma média de precisão ao longo de múltiplos limiares de IOU, também apresentou um aumento significativo (de 0.421 para 0.544). Isso mostra uma melhoria geral no desempenho do modelo em diferentes limiares.

2. Tratores vs Casas:
O desempenho com tratores foi melhor tanto em precisão quanto em recall, provavelmente porque o modelo teve mais exemplos de tratores, o que ajudou no aprendizado. Já para as casas, o modelo tem um desempenho razoável, com uma boa precisão, mas poderia melhorar ainda mais.

*Mais experimentos são necessários para otimizar ainda mais o modelo, com mais dados e ajustes finos.*



## 🖼️ Prints dos resultados

📌 Imagem trator

![image](https://github.com/user-attachments/assets/49645ecf-8c44-483c-92ec-bc45f1d04987)


📌 Imagem casa

![image](https://github.com/user-attachments/assets/b6fda0f6-67dd-45ee-8025-db4a7c5a8c14)




## 📊 Link video

https://youtu.be/i6o_5E1ckbo


## Historico de lançamentos

- <b> 0.1.0 - 28/04/2025<b>

  
## 📋 Licença

<img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/agodoi/template">MODELO GIT FIAP</a> por <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://fiap.com.br">Fiap</a> está licenciado sobre <a href="http://creativecommons.org/licenses/by/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution 4.0 International</a>.</p>
