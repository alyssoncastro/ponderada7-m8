# Classificação do MNIST com Rede Neural Convolucional

#### AUTOR: ALYSSON C. C. CORDEIRO.

Este projeto treina e utiliza uma rede neural convolucional para classificar corretamente o dataset MNIST, que consiste em dígitos manuscritos.

### Instalação

Clone o repositório para sua máquina local:

```python
git clone https://github.com/alyssoncastro/ponderada7-m8.git
```

Navegue até o diretório do projeto:

```python 
cd ponderada7
```

Instale as dependências necessárias. Certifique-se de ter o Python e o pip instalados. Use os seguintes comandos:

```python
pip install numpy
pip install matplotlib
pip install tensorflow
pip install keras
```

obs: se você está usando o Google Colab, não será necessário instalações.

---

## Descrição do Código

O código principal, neural.ipynb, contém a implementação da rede neural convolucional. Utilizamos o TensorFlow e Keras para criar e treinar a arquitetura da rede.

## Arquitetura da Rede Neural

A arquitetura do modelo está definida no arquivo neural.ipynb utilizando camadas convolucionais, de pooling e camadas densas.
Os parâmetros da rede podem ser ajustados para experimentar com diferentes configurações.

## Treinamento do Modelo

O modelo é treinado com o conjunto de dados MNIST, buscando uma acurácia superior a 95% em 3 épocas.

## Ambiente de Desenvolvimento

Este projeto foi desenvolvido no Visual Studio Code com a extensão Jupyter Notebook, facilitando o desenvolvimento interativo e a experimentação com o código.

## vídeo: