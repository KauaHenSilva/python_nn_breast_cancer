# Breast Cancer Neural Network Projects

## Open In Colab
Este projeto pode ser executado diretamente no Google Colab para facilitar a visualização e execução dos notebooks.

## Notebooks

Este repositório contém três Jupyter Notebooks que exploram diferentes técnicas de treinamento de redes neurais para classificação de câncer por meio de manchas na pele. Cada notebook foca em um aspecto específico do treinamento de modelos.

### Notebooks Disponíveis:

#### 1. breast_cancer_simples.ipynb [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KauaHenSilva/python_nn_breast_cancer/blob/main/breast_cancer_simples.ipynb)
Demonstra um modelo de rede neural simples para classificação de câncer de mama, abordando carregamento de dados, pré-processamento e treinamento usando TensorFlow.

#### 2. breast_cancer_cruzada.ipynb  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KauaHenSilva/python_nn_breast_cancer/blob/main/breast_cancer_cruzada.ipynb)
Explora técnicas de validação cruzada para avaliar o modelo. Inclui a implementação de uma camada de dropout para evitar overfitting e utiliza o `KerasClassifier` para encapsulamento do modelo.

#### 3. breast_cancer_tuning.ipynb  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/KauaHenSilva/python_nn_breast_cancer/blob/main/breast_cancer_tuning.ipynb)
Foca na otimização de hiperparâmetros utilizando `GridSearchCV` para encontrar os melhores valores de configuração, melhorando a acurácia do modelo.

## Como Usar no Google Colab
Para executar os notebooks no Google Colab, siga os passos abaixo:

1. **Acesse o Google Colab**
   - Abra o Google Colab.

2. **Carregue o Notebook**
   - Clique em Arquivo > Abrir notebook.
   - Escolha a aba GitHub e insira o link deste repositório.
   - Selecione um dos notebooks disponíveis.

3. **Baixe os Dados Necessários**
   - Os dados podem ser baixados automaticamente executando as células que carregam os arquivos do Google Drive ou de um repositório externo.

4. **Execute as Células**
   - Conecte-se ao ambiente clicando em "Conectar" no canto superior direito.
   - Execute as células sequencialmente para treinar e avaliar o modelo.

## Instalação
Para executar o código localmente, instale as dependências necessárias com o seguinte comando:

```bash
pip install tensorflow==2.16.1 scikit-learn==1.5.0 scikeras==0.13.0
```

## Agradecimentos
Este projeto foi desenvolvido para demonstrar diferentes abordagens na criação e otimização de redes neurais para classificação de câncer de mama, utilizando TensorFlow, Scikit-learn e Scikeras.

