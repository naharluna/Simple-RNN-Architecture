# Simple RNN Architecture

Welcome to the **Simple RNN Architecture** repository! This project demonstrates the implementation of a basic Recurrent Neural Network (RNN) using Keras to perform sequence modeling tasks. The repository is designed for educational purposes, providing insights into how RNNs process sequential data and generate predictions.

## Project Overview

This repository includes:

- A simple RNN architecture with a `SimpleRNN` layer and a `Dense` output layer.
- Model construction using the Keras Sequential API.
- Inspection of model weights for better understanding of RNN parameters.

## Code Highlights

1. **Model Architecture:**
   - Input layer: Accepts sequences of shape `(4, 5)`.
   - Simple RNN layer: Contains 3 units.
   - Output layer: A single neuron with a sigmoid activation function for binary classification tasks.

2. **Weight Inspection:**
   - The code prints and analyzes the shapes and values of the model weights, including recurrent weights, biases, and kernel weights.

## Prerequisites

Before running the code, ensure you have the following installed:

- Python 3.7+
- TensorFlow/Keras

You can install the required packages using pip:

```bash
pip install tensorflow
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/naharluna/simple-rnn-architecture.git
```

2. Navigate to the project directory:

```bash
cd simple-rnn-architecture
```

3. Run the code:

```bash
python simple_rnn.py
```

## Output

The code outputs the model summary and prints the shapes and values of key model weights, giving insights into how the RNN processes sequential data.

## Learn More

- [Keras Documentation](https://keras.io/)
- [SimpleRNN Layer](https://keras.io/api/layers/recurrent_layers/simple_rnn/)

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for details.

---

**Author:** Badrun Nahar Luna
