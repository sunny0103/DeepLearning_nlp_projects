# Movie Review Text classification
### Data Source: Dacon

### Problem Statement: Classify Positive and negative sentiment of movie reviews

### Model Details:
#### BERT ("klue/bert-base")
* max len = 64
* batch size = 16
* warmup ratio = 0.1
* num epochs = 10
* max grad_norm = 1
* learning rate =  2e-5
* dropout rate = 0.2
* Train Loss: 0.0016
* Train Accuracy:0.9992
* Valid Accuracy:0.9177
* Test Private score: 0.916
* Test Public score: 0.9263
