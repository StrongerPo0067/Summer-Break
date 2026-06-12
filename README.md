# Quantitative Risk Engine & Distorted CAPTCHA Recognition

This repository contains two core machine learning prototypes implemented via Jupyter Notebooks:
1. `market.ipynb`: A quantitative trading and portfolio risk allocation engine utilizing a Random Forest classifier and an interactive dashboard.
2. `Notebook_Aaditya_Pratap_24113001.ipynb`: A deep learning Sequence Recognition framework utilizing a Convolutional Recurrent Neural Network (CRNN) and CTC Loss.

## Environment Setup
* **Python Version:** Python 3.12+ is required.
* **Hardware:** A CUDA-enabled GPU is highly recommended for executing the PyTorch CRNN training loop in the CAPTCHA notebook. The quantitative trading notebook runs efficiently on a standard CPU.
* **Environment:** A functional Jupyter environment (e.g., JupyterLab, Jupyter Notebook, or VS Code with Jupyter extensions) is required to render the code and the `ipywidgets` interactive dashboard.

## Dependency Installation
The notebooks rely on standard data science and deep learning libraries. Install the required dependencies using the following command in your terminal:

```bash
pip install pandas numpy scikit-learn matplotlib ipywidgets torch torchvision pillow tqdm tensorboard
