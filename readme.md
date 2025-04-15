# Fine-tuned LLM for telecommunication

## Introduction

Fine-tuning LLMs is crucial for enhancing their performance on specific tasks and domains, leading to improved accuracy, efficiency, and the ability to perform specialized tasks. It allows models to better understand specific jargon, styles, and knowledge, making them more versatile and effective in real-world applications.

## Depolyment

This prototype depolyed on Windows, and it is written in Python.

### Requirements:

    Transformers
    Python 3.8
    Torch 2.0.1

### Set up

1. **Install all dependencies**
   ```
   pip install -r requirements
   ```
2. **fine_tune.ipynb only fine-tuned with Q/A, fine_tune_with_option trained with multiple choices.**
3. **put your own corpus and change the file path in fine_tune.ipynb or fine_tune_with_option.ipynb**
4. **Execute the fine_tune.ipynb or fine_tune_with_option.ipynb**
5. **Ask questions to your own fine-tuned LLM**
