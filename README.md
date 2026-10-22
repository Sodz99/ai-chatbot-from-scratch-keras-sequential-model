# Build an AI Chatbot from Scratch using Keras Sequential Model

1.

## Overview
Companies depend on large and round-the-clock support staff to maintain customer engagement. This can be costly and impractical. Chatbots can effectively boost efficiency and lower the cost of business. It resolves unlimited queries with the least human interaction. Creating robust chatbot training data is costly in terms of human time and effort. Additionally, it increases the product design to deployment time. Companies with only a minimal amount of training data may not be able to produce a robust enough model to use for chatbot interactions. In this project, we will use internal customer support data to create a robust chatbot using the Sequential model. It also demonstrates how to run the chatbot by using the developed model.

## Data
The dataset is an unstructured assortment of ProjectPro customer service inquiry chat logs. The chat logs consist of timestamped dialogue between a human customer agent and a visitor to the ProjectPro website. The dialogue consists predominately of queries about ProjectPro's services, prices, location, and signup information.

_Data is not included in this repository._

## Approach
1. Preprocess semi-structured data
2. Perform exploratory data analysis
3. Unsupervised labeling
4. Supervised labeling
5. Training data preparation
6. Hyperparameter tuning
7. Train deep learning sequential model
8. Evaluating the model
9. Use model for prediction
10. Run the chatbot

Note: Kindly refer README.MD file to run all the code files.

## Tech stack
➔ Language: Python ➔ Libraries: pandas, numpy, seaborn, spacy, tensorflow, sklearn, nltk, matplotlib, hyperopt, keras, chatintents

## How to run
```bash
pip install -r code (1)/src/requirements.txt
python code (1)/src/ML_Pipeline/train.py
python code (1)/src/engine.py
```
Notebooks: [`chatbot.ipynb`](code%20(1)/chatbot.ipynb)

## Project structure
```
.gitignore
README.md
code (1)/
  README.MD
  chatbot.ipynb
  src/
    ML_Pipeline/
    engine.py
    requirements.txt
```

## Credits
Based on a ProjectPro guided project.
