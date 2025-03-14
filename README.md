# Improving OOD and OSR Detection in Traffic Sign Recognition using data from the wild

## Overview
This project explores out-of-distribution (OOD) detection as a crucial technique for improving recognition accuracy in autonomous vehicles. Traditional classification models operate under the closed-world assumption, meaning they assume test data will always come from the same distribution as the training data. However, in real-world scenarios, an autonomous vehicle may encounter novel objects not present in its training set. Without the ability to recognize unfamiliar inputs, the model might misclassify these objects, potentially leading to dangerous outcomes.

Traffic sign recognition is a specialized case of the broader object recognition problem, which plays a vital role in autonomous driving. To simplify our study, we focus specifically on traffic sign recognition, as it allows for smaller datasets and reduced training time while still providing insights that may generalize to broader object recognition challenges. By integrating OOD detection techniques, we aim to enhance model reliability and safety in real-world driving conditions.

## Project Structure
```
├── data/                   # Dataset used for training and evaluation
├── models/                 # Saved models and checkpoints
├── scripts/                # Training and evaluation scripts
├── results/                # Performance metrics and analysis
├── README.md               # Project documentation
└── requirements.txt        # Required dependencies
```

## Methodology


## Experiment Setup
- **Model:** [Specify the transformer model used, e.g., BERT, GPT, T5]
- **Dataset:** [Specify dataset used, e.g., IMDb, AG News, etc.]
- **Hardware:** [GPU details if applicable]
- **Framework:** PyTorch + Hugging Face Transformers

## Results


### Key Observations


## Installation
To set up the environment, run:
```sh
pip install -r requirements.txt
```

## Running Experiments
To train using standard fine-tuning:
```sh
python scripts/train.py --method standard
```
To train using LoRA:
```sh
python scripts/train.py --method lora
```
To evaluate models:
```sh
python scripts/evaluate.py --model_path models/your_model.pth
```

## Future Work


## References
- 
- 
- 

---
© 2025 Ahmed Nassar

