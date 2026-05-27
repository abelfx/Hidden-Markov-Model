# Hidden Markov Model (HMM)

This repository contains a Jupyter Notebook implementation and examples for Hidden Markov Models (HMMs). It demonstrates core concepts, parameter estimation, and decoding (Viterbi) using Python.

Contents
- `Hidden_Markov_Model.ipynb` — interactive notebook with explanations and runnable examples.

Quick start
1. Create and activate a Python virtual environment (recommended):
    ```
	python -m venv .venv
	source .venv/bin/activate
    ```

2. Install dependencies:
    ```
	pip install -r requirements.txt
    ```

3. Launch the notebook:
    ```
	jupyter notebook Hidden_Markov_Model.ipynb
    ```

Usage
- Run the notebook cells in order. The notebook includes sections for:
  - model definition and initialization
  - training/parameter estimation (Baum–Welch)
  - decoding (Viterbi)

Dependencies
- See `requirements.txt` for the Python packages used by the notebook.

## Dataset
This project was trained and evaluated using the **English Web Treebank (EWT)**, provided by the [Universal Dependencies](https://universaldependencies.org/) framework. 

* **Repository:** [UD_English-EWT](https://github.com/UniversalDependencies/UD_English-EWT)
* **Training Data:** `en_ewt-ud-train.conllu`
* **Size:** ~20,000 words annotated with 18 Universal POS tags.