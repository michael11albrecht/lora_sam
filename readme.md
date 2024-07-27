# LoRa SAM: Fine-Tuning SAM Model with LoRa

This repository contains code and notebooks for fine-tuning and testing the SAM model by Meta using the LoRa technique developed by Microsoft. The implementation leverages the Hugging Face Transformers API for ease of use.
Basically it's just a training algorithm enhancing LoRa used to finetune LLMs adapted to training a vision transformer model like SAM.

## Introduction

The LoRa SAM project applies the Low-Rank Adaptation (LoRa) technique, originally developed for fine-tuning large language models, to a vision transformer model. This repository includes two Jupyter notebooks:

1. `train_loarasam.ipynb` - Notebook for fine-tuning the SAM model.
2. `test_lorasam.ipynb` - Notebook for testing the fine-tuned SAM model.

## Usage:

The Notebooks are build to be run e.g. Google Colab, thats why all the requirements are listed as commands at the beginning of the notebook.

## Credits

- [SAM-Model](https://segment-anything.com) by Meta.
- [The Lora paper](https://arxiv.org/abs/2106.09685) by Microsoft.
- [Hugging Face Transformers](https://huggingface.co/docs/transformers/index)

## License

TODO