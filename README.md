

# PT-BR Kaggle Digit Recognizer Challenge

Este projeto foi desenvolvido para abordar o desafio do Kaggle "Digit Recognizer". O desafio envolve a classificação de dígitos manuscritos de zero a nove. Os dados de treinamento consistem em imagens em escala de cinza de 28x28 pixels, totalizando 784 pixels por imagem.

## Conjunto de Dados

Os conjuntos de dados de treinamento e teste podem ser encontrados [aqui](https://www.kaggle.com/competitions/digit-recognizer/data?select=test.csv). O arquivo `train.csv` contém as imagens de treinamento com rótulos, enquanto o arquivo `test.csv` contém as imagens de teste sem rótulos.

## Arquivo Python - digit_recognition.py

O arquivo `digit_recognition.py` contém o código-fonte Python para abordar o desafio. O script realiza as seguintes etapas:

1. **Leitura e Exploração dos Dados:** Carrega e explora os conjuntos de treinamento e teste.
2. **Visualização dos Dados:** Exibe algumas imagens do conjunto de treinamento e verifica a distribuição dos rótulos.
3. **Pré-Processamento dos Dados:** Normaliza os valores dos pixels e prepara os dados para treinamento.
4. **Treinamento do Modelo:** Usa um modelo de Support Vector Machine (SVM) para treinar o reconhecimento de dígitos.
5. **Avaliação do Modelo:** Avalia o desempenho do modelo usando métricas como precisão.
6. **Previsões no Conjunto de Teste:** Faz previsões no conjunto de teste usando o modelo treinado.
7. **Criação do Arquivo de Envio:** Gera um arquivo CSV conforme as especificações do Kaggle para submissão.

## Como Executar o Código

Certifique-se de ter as bibliotecas necessárias instaladas. Você pode instalá-las usando:

```bash
pip install -r requirements.txt
```

Execute o script usando:
`python digit_recognition.py`


# EN Kaggle Digit Recogniser Challenge

This project was developed to tackle the Kaggle "Digit Recogniser" challenge. The challenge involves classifying handwritten digits from zero to nine. The training data consists of 28x28 pixel grey-scale images, totalling 784 pixels per image.

## Data Set

The training and test data sets can be found [here](https://www.kaggle.com/competitions/digit-recognizer/data?select=test.csv). The `train.csv` file contains the labelled training images, while the `test.csv` file contains the unlabelled test images.

## Python file - digit_recognition.py

The file `digit_recognition.py` contains the Python source code for tackling the challenge. The script performs the following steps:

1. **Data Reading and Exploration:** Loads and explores the training and test sets.
2. **Data Visualisation:** Displays some images from the training set and checks the distribution of the labels.
3. **Data Pre-Processing:** Normalises the pixel values and prepares the data for training.
4. **Model Training:** Uses a Support Vector Machine (SVM) model to train digit recognition.
5. **Model Evaluation:** Evaluates the model's performance using metrics such as accuracy.
6. **Test Set Predictions:** Makes predictions on the test set using the trained model.
7. **Submission File Creation:** Generates a CSV file according to Kaggle's specifications for submission.

## How to Run the Code

Make sure you have the necessary libraries installed. You can install them using:

```bash
pip install -r requirements.txt
```

Run the script using:
`python digit_recognition.py`
