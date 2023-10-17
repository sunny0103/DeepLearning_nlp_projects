# News Group Classification Model Evaluation
### Data Source: Dacon

### Problem Statement: Develop an algorithm to classify news groups(Multiclass classification)

### Model Details:

* Maximum Length: 512
* Batch Size: 16
* Learning Rate: 2e-5
* 
#### BERT ("bert-base-uncased")
* Epoch:3
* Train Loss: 0.451
* Validation Loss: 0.930
* Accuracy: 0.733
* Test Public score: 0.7071057192
* Test Private score: 0.7028373403

#### Electra ('google/electra-base-discriminator')
* Epoch:4
* Train Loss: 0.517
* Validation Loss: 0.988
* Accuracy: 0.720
* Test Public score: 0.7084055459
* Test Private score: 0.7080355209

#### Roberta ('xlm-roberta-base')
* Epoch:3
* Train Loss: 0.653
* Validation Loss: 0.961
* Accuracy: 0.718
* Test Public score: 0.7034228769
* Test Private score: 0.7069525666


#### Ensemble 
* Test public score: 0.7469670711
* Test private score: 0.7416071042
  
