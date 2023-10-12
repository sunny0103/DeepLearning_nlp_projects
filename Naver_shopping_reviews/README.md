# Naver shopping reviews classification
### Data Source: Dacon

### Problem Statement: classify online shopping reviews into four different classes
### Model Details:

* Maximum Length: 512
* Batch Size: 16

#### BERT ('jason9693/SoongsilBERT-base-beep')
* Learning Rate: 2e-5
* Epoch:1
* Train loss: 0.790
* Validation loss: 0.731
* Accuracy: 0.684

####  Electra ('kykim/electra-kor-base')
* LEARNING_RATES = 2e-6
* Epoch:4
* Train loss: 0.632
* Validation loss: 0.688
* Accuracy: 0.711

#### Roberta ('jason9693/klue-roberta-small-apeach')
* LEARNING_RATES = 2e-5
* Epoch:2
* rain loss: 0.680
* Validation loss: 0.749
* Accuracy: 0.684


#### Funnel(kykim/funnel-kor-base)
* LEARNING_RATES = 2e-5
* Epoch:1
* Train loss: 0.754
* Validation loss: 0.693
* Accuracy: 0.707
* Test Public score:: 0.6996
* Test Private score: 0.70552

#### Ensemble 
* Test public score:
* Test private score:
  

