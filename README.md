# Swim Coach Language Model Fine-Tuning

## Authors
- Reggie Wade

This project fine-tunes a lightweight version of LLaMA (`TinyLlama-1.1B`) using LoRA (Low-Rank Adaptation) to create a specialized language model that gives technical feedback on freestyle swim technique. The notebook includes the full pipeline: data augmentation, fine-tuning, and evaluation using BLEU and ROUGE metrics.

## Contents

- `final_project.ipynb` – Main notebook that runs the entire project.
- `swim-dataset.csv` - Dataset used to fine-tune model TinyLlama
- `requirements.txt` - Install dependencies
- Training and evaluation logs.
- BLEU/ROUGE performance metrics.

## Setup Instructions

### 1. Clone the repository

```bash
git clone git@github.com:reggiewade/swim-chatbot.git
cd swim-chatbot
```

### 2. Download required dependencies
```bash
pip install -r requirements.txt
```
Depending on the machine being used, steps to install cuda can vary, check this link for your OS: https://developer.nvidia.com/cuda-downloads</br>
If on macOS, look here for how to install pytorch with metal: https://developer.apple.com/metal/pytorch/.  Howver, I have not tried to run this code on macOS so there may be pieces of code that need tweaking.

### 3. Step through jupyter notebook

From here, stepping through the notebook should provide similar results.  The dataset is small enough that I have kept it in the actual github repo.