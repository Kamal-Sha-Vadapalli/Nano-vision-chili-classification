# Nano-Vision: Chilli Leaf Classification (Prototype)

## Overview
This repository contains a prototype image classification system for identifying
plant stress conditions in chilli leaves using transfer learning.

## Model
- Architecture: EfficientNetB0 (pretrained on ImageNet)
- Method: Transfer learning with selective fine-tuning
- Framework: TensorFlow / Keras

## Data
- Trained using publicly available plant leaf image datasets
- Data augmentation applied
- No field-level or farmer-collected image validation

## Results
- Performance evaluated on a validation split
- Metrics include accuracy, precision, recall, and F1-score
- Results reflect curated dataset performance, not real-world deployment

## Limitations
- Trained on public datasets under controlled conditions
- Performance may degrade on real-world images
- Visual symptoms of nutrient deficiency and disease can overlap
- Predictions are not agronomic or medical advice

## Status
This project is part of an ongoing academic exploration.
The accompanying research paper is currently in preparation.
## Working model
A web interface of this model is deployed in Hugging Face Spaces: https://huggingface.co/spaces/Kamal-Sha/Chilli-Classification
