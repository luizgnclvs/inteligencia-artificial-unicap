# Otimização de Hiperparâmetros de Redes Neurais Perceptron Multi-Camadas (MLP)

Os hiperparâmetros a serem otimizados são número de camadas escondidas e número de neurônios em cada uma destas camadas escondidas.

- Baixar uma base de dados de classificação na [UCI ML Repository](https://archive.ics.uci.edu/ml/index.php)
- Criar diferentes modelos de Redes Neurais MLP usando as seguintes configurações:
  - Variar o número de camadas escondidas entre 1, 5, 7, 10
  - Variar o número de neurônios das camadas escondidas entre 25, 50, 100, 200, 500
  - Combinar os números de camadas e neurônios e terão 20 configurações diferentes de Redes Neurais
- Treinar cada configuração de modelo de redes neurais
- Avaliar a acurácia de teste de cada modelo
- Ao final, escrever um relatório indicando os fenômenos observados

É necessário adicionar o arquivo *balance-scale.data* ao notebook do Colab antes de executá-lo.
