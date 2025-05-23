# Classificação de Análises de Produtos com Hugging Face Accelerate 🚀

[![Python](https://img.shields.io/badge/python-3.8%2B-blue.svg)](https://www.python.org/)

Projeto de demonstração para utilização da biblioteca **Hugging Face Accelerate** no treinamento de modelos de IA para análise de sentimentos e classificação de análises de produtos em uma loja virtual.

---

## ✨ Visão Geral

O objetivo deste projeto é demonstrar como utilizar o [Hugging Face Accelerate](https://github.com/huggingface/accelerate) para facilitar e agilizar o treinamento de modelos em diferentes ambientes (CPU, GPU, multi-GPU, etc). Utilizamos um cenário realista, onde uma loja virtual deseja classificar os sentimentos presentes nas análises de produtos feitas por seus clientes, possibilitando melhores insights e tomadas de decisão.

---

## 📚 Tecnologias Utilizadas

* [Python 3.8+](https://www.python.org/)
* [Hugging Face Accelerate](https://huggingface.co/docs/accelerate/index)
* [Transformers (Hugging Face)](https://huggingface.co/docs/transformers/index)
* [Datasets (Hugging Face)](https://huggingface.co/docs/datasets/)
* [PyTorch](https://pytorch.org/)

---

## ⚡ Instalação e Uso

### 1. Clone o repositório

```bash
git clone https://github.com/Joaovmir/Zero-shot-model-accelerate.git
cd Zero-shot-model-accelerate
```

### 2. Instale as dependências

No Google Colab, as dependências principais são instaladas nas primeiras células do notebook.

Localmente, execute:

```bash
pip install accelerate transformers datasets torch
```

### 3. Execute o Notebook

Abra e execute o arquivo `Hugging_Face_com_Accelerate.ipynb` em seu ambiente de preferência.

---

## 💡 Exemplo de Uso

Este projeto utiliza a base de dados [`multilingual-NLI-26lang-2mil7`](https://huggingface.co/datasets/MoritzLaurer/multilingual-NLI-26lang-2mil7), com exemplos de premissas e hipóteses em várias línguas, para criar um classificador de sentimentos.

Após treinar o modelo, você poderá analisar e classificar novos comentários automaticamente.

---

## 📁 Estrutura do Projeto

```
classificacao-acelerada-huggingface/
├── Hugging_Face_com_Accelerate.ipynb
├── README.md
```
