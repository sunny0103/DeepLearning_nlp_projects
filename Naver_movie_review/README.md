# News Group Classification Model Evaluation
### Data Source: Dacon

### Problem Statement: Develop an algorithm to classify news groups(Multiclass classification)

### Model Details:
 
#### Bidirectional RNN with Torch Text (Fasttext)
* input_size = 10003
* word_vec_size = 100
* hidden_size = 128
* learning_rate = 0.01
* NUM_EPOCHS=5
* optimizer = Adam

#### GRU
* input_size = vocab_size
* word_vec_size = 100
* hidden_size = 128
* learning_rate = 0.001
* NUM_EPOCHS=5
  
