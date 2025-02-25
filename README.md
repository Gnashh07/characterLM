## Character-Level Language Model

### About This Project

This is a character-level language model built from scratch, inspired by Andrej Karpathy’s work. The goal is to generate text one character at a time(generate random names) by training a deep learning model. The model learns character dependencies and can generate sequences based on its training data.
I built this project because I wanted to understand how ChatGPT works. This is an effort to explore the inner workings of large language models by implementing a character-level version of it—a tiny GPT, so to speak.&#x20;

### Features

- Implements a character-level language model from the ground up.
- Uses `torch`, `torch.nn.functional`, `random`, `requests`, and `matplotlib.pyplot`.
- Includes key functions:
  - `build_dataset` for dataset preparation.
  - `split_loss` to measure model performance.
- Custom-built neural network components inspired by the PyTorch library:
  - `BatchNorm1d`
  - `Sequential`
  - `Linear`
  - `Embedding`

### Contributing

If you have ideas or improvements, feel free to fork the repository and submit a pull request.

