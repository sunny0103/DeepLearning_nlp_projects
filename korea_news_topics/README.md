# News Topic Classification Model Evaluation
### Data Source: Dacon

### Problem Statement: Develop an algorithm to classify news topics using Korean news headlines.

### Model Details:

#### BERT ('jason9693/SoongsilBERT-base-beep')
* Maximum Sequence Length: 64
* Batch Size: 16
* Learning Rate: 5e-5
* Number of Epochs: 2
* Accuracy: 0.848

#### RoBERTa ('Huffon/klue-roberta-base-nli')
* Maximum Sequence Length: 64
* Batch Size: 16
* Learning Rate: 2e-6
* Number of Epochs: 3
* Accuracy: 0.887

### Results:
* BERT achieved an accuracy of 0.848 after 2 training epochs.
* RoBERTa outperformed BERT, achieving an accuracy of 0.887 after 3 training epochs.
