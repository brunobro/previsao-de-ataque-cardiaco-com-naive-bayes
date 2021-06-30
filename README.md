# Previsão de Change de Ataque Cardíaco com Naive Bayes

Neste vídeo-tutorial (disponível em https://youtu.be/yxrutEGxFhY) aprenderemos como criar um algoritmo de aprendizado de máquina (machine learning) capaz de aprender se um paciente terá mais ou menos chance de ter uma ataque cardíaco analisando as variávies:

Variáveis preditoras:
  * age: Idade do paciente

  * sex: Sexo do paciente

  * exang: angina induzida por exercício (1 = sim; 0 = não)

  * ca: número de grandes vasos (0-3)

  * cp: tipo de dor no peito (angina)

    * Valor 1: angina típica
    * Valor 2: angina atípica
    * Valor 3: dor não anginosa
    * Valor 4: assintomático

  * trtbps: pressão arterial em repouso (em mm Hg)
  * chol: colestoral em mg/dl obtido por meio do sensor de IMC
  * fbs: (açúcar no sangue em jejum> 120 mg / dl) (1 = verdadeiro; 0 = falso)
  * rest_ecg: resultados eletrocardiográficos em repouso
    * Valor 0: normal
    * Valor 1: tendo anormalidade da onda ST-T (inversões da onda T e / ou elevação ou depressão do ST> 0,05 mV)
    * Valor 2: mostrando hipertrofia ventricular esquerda provável ou definitiva pelos critérios de Estes
  * thalach: frequência cardíaca máxima alcançada

Variável predita:
  * 0 = menos chance de ataque cardíaco
  * 1 = mais chance de ataque cardíaco

<img src="heart.png">
