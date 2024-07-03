# QA_with_PDF_LLMs
#### Your computer must have GPU to run it
## 1. Installation
`conda` virtual environment is recommended
```
conda create -n QA_PDF_env python=3.9 -y
conda activate QA_PDF_env
```
After that you access [Start Locally Pytorch](https://pytorch.org/get-started/locally/) to install pytorch.
```
pip install -r requirements.txt
```
## 2. Usage
First:
```command
cd QA_with_PDF_LLMs
conda activate QA_PDF_env
```
### 1. Use local
```python
chainlit run app.py
```
### 2. Use ngrok to share
```python
chainlit run app.py
ngrok http 8000
```