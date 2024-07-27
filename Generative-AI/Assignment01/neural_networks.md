
# Neural Networks

## Introduction
Neural networks are a subset of machine learning algorithms inspired by the human brain's structure and function. They consist of interconnected layers of nodes, or neurons, that process and transmit information. Neural networks are used in various applications, including image recognition, natural language processing, and autonomous systems.
![neurons_biais](https://github.com/user-attachments/assets/e7a83f58-4b64-45fb-a53e-c711500f2a82)


## Structure of Neural Networks
- **Neurons**: The basic units of a neural network, analogous to brain cells. Each neuron receives input, processes it, and passes the output to the next layer.
- **Layers**: Neural networks are composed of multiple layers:
  - **Input Layer**: The layer that receives the initial data.
  - **Hidden Layers**: Intermediate layers that transform the input data through a series of weighted connections and activation functions.
  - **Output Layer**: The final layer that produces the network's output.

## Parameters
![nural_waight](https://github.com/user-attachments/assets/8d61451f-a18f-4f52-9eb5-4b913ccc8ac5)

**Parameters** are the internal values that a neural network adjusts during the training process to learn from data. They include:
- **Weights**: Each connection between neurons has an associated weight that determines the importance of the input value. Weights are adjusted during training to minimize the error in the network's predictions.
- **Biases**: Additional parameters added to the input of each neuron to allow the model to better fit the data. Biases help shift the activation function to better match the data.
![neurons_biais](https://github.com/user-attachments/assets/be30e81c-1d22-429d-86e2-5ac7aa0c1154)

### Training Neural Networks
Training a neural network involves the following steps:
1. **Forward Propagation**: Input data is passed through the network, layer by layer, to generate an output.
2. **Loss Calculation**: The output is compared to the actual target value using a loss function to calculate the error.
3. **Backward Propagation**: The error is propagated back through the network, and the weights and biases are adjusted using optimization algorithms like gradient descent to minimize the error.
4. **Iteration**: Steps 1-3 are repeated for multiple epochs until the network's performance is satisfactory.

## Tokens
**Tokens** are the basic units of data used in natural language processing (NLP) tasks. They can be words, subwords, or characters, depending on the tokenization strategy. Tokens are used to convert text into a format that neural networks can process.
- **Word Tokens**: Entire words are treated as individual tokens.
  - Example: "Neural networks are fascinating." -> ["Neural", "networks", "are", "fascinating"]
- **Subword Tokens**: Words are broken down into smaller units, allowing the model to handle unknown words and reduce the vocabulary size.
  - Example: "Unbelievable" -> ["Un", "believable"]
- **Character Tokens**: Individual characters are used as tokens, which can handle any text but result in longer sequences.
  - Example: "Hello" -> ["H", "e", "l", "l", "o"]
![Uploading transformer-tokenization-and-embeddings.drawio.svg…]()

## Summary
Neural networks are powerful machine learning models composed of neurons and layers that process data. Parameters like weights and biases are adjusted during training to learn from data and make accurate predictions. In NLP tasks, tokens are the fundamental units of data that neural networks use to process and understand text.

