# News Topic Classification Model Evaluation
### Data Source: Dacon

### Problem Statement: Develop an algorithm to classify news topics using Korean news headlines.

### Model Details:

#### BERT ('jason9693/SoongsilBERT-base-beep')
* Maximum Length: 64
* Batch Size: 16
* Epoch:2,
* Train loss: 0.309,
* Validation loss: 0.418,
*  Accuracy: 0.862

#### RoBERTa ('Huffon/klue-roberta-base-nli')
* Maximum Length: 64
* Batch Size: 16
* Learning Rate: 2e-6
* Epoch:3,
* Train loss: 0.254,
* Validation loss: 0.325,
* Accuracy: 0.887

### Results:
* BERT achieved an accuracy of 0.848 after 2 training epochs.
* RoBERTa outperformed BERT, achieving an accuracy of 0.887 after 3 training epochs.
