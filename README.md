# AI or Human Made Art Classifier

This repository hosts a TensorFlow model capable of distinguishing between AI-generated and human-made art. It utilizes the "AI and Human Art Classification" dataset from Kaggle, accessible at [this link](https://www.kaggle.com/datasets/kausthubkannan/ai-and-human-art-classification).

## Project Structure

- `data/`: Contains the dataset, organized into subfolders for AI and Human categories.
- `models/`: Stores the trained model file.
- `logs/`: Holds TensorBoard logging data for training visualization.

## Installation

Clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/Meriiem/AI-or-Human-Made-Art
cd AI-or-Human-Made-Art
```

## Model Details
The architecture includes convolutional layers, max pooling, flattening steps, and dense layers. It uses binary cross-entropy for loss and accuracy for evaluation metrics.

## Training and Evaluation
Data is split into 70% training, 20% validation, and 10% test sets.
