# Qlora-Peft-LLMs-Prompt-Generation


This repository contains implementations of prompt generation using the Qlora method and the PEFT (Parameter-Efficient Fine-Tuning) approach. The project leverages the TinyLlama model and utilizes the `BitsAndBytesConfig` for loading the model in 8-bit configuration, ensuring efficient computation. It includes notebooks for both Kaggle and Google Colab, showcasing model performance and prompt generation capabilities.

## Features

- Efficient prompt generation utilizing the Qlora method
- Implemented in both Kaggle and Google Colab notebooks
- Demonstrates model performance metrics using TensorBoard
- Easy-to-use interface for generating prompts based on user-defined titles

## Model and Dataset

- **Model**: The project uses the TinyLlama model: [TinyLlama/TinyLlama-1.1B-intermediate-step-1431k-3T](https://huggingface.co/TinyLlama/TinyLlama-1.1B-intermediate-step-1431k-3T) from Hugging Face.
- **Dataset**: The dataset used for training and prompt generation is [fka/awesome-chatgpt-prompts](https://huggingface.co/datasets/fka/awesome-chatgpt-prompts) from Hugging Face.

## Installation

To run the notebooks, ensure you have the following libraries installed. A `requirements.txt` file is included for easy installation:

```bash
pip install -r requirements.txt
```

## Model

The trained model is saved in zip format for easy access and deployment. Ensure to unzip the model before use. The model is configured with `BitsAndBytesConfig` to load it in 8-bit format for optimized performance.

## Usage

The notebooks in this repository demonstrate how to generate prompts based on user-defined titles. Both Kaggle and Google Colab notebooks are included for ease of access.

### Notebooks

- **Kaggle Notebook**: [Open Kaggle Notebook](https://github.com/Warishayat/Qlora-Peft-LLM-s/blob/main/llms-peft-lora.ipynb) 
- **Google Colab Notebook**: [Open Google Colab Notebook](https://github.com/Warishayat/Qlora-Peft-LLM-s/blob/main/LLMs_Peft.ipynb)

## Model Performance

Performance metrics of the model can be found within the [Performance Directory](https://github.com/Warishayat/Qlora-Peft-LLM-s/tree/main/Performance), with visualizations provided through TensorBoard. These metrics showcase the effectiveness of the prompt generation and fine-tuning processes.

## Contributing

Contributions are welcome! If you'd like to contribute to this project, please fork the repository and submit a pull request.

## License

This project is licensed under the Apache 2.0 License. See the [LICENSE](LICENSE) file for details.
