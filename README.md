# Boolean Question Answering using T5

## Overview

This project implements and optimizes a T5-based model for boolean question answering using the BoolQ dataset. We explore various hyperparameters to enhance model performance and provide insights into its strengths and limitations.

## Key Features

- Utilizes the T5 model for text-to-text transformation
- Comprehensive hyperparameter analysis (learning rate, batch size, sequence length, warmup steps)
- Achieves 76.5% validation accuracy with optimized settings
- In-depth error analysis across different question categories

## Optimal Configuration

- Learning Rate: 1e-4
- Batch Size: 8
- Sequence Length: 512
- Warmup Steps: 600

## Results Highlights

- 82.3% training accuracy
- 76.5% validation accuracy
- Strong performance on simple yes/no questions (90% accuracy)
- Challenges with complex, multi-step reasoning questions

## Future Improvements

- Gradient accumulation for larger effective batch sizes
- Advanced data augmentation techniques
- Integration of external knowledge bases
- Implementation of adversarial training


## Date

November 2024
