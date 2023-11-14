# Naver Movie Review Classification Model Evaluation
### Data Source: Github (https://raw.githubusercontent.com/e9t/nsmc/master)

### Problem Statement: Develop an algorithm to classify Positive and negative sentiment of movie reviews

### Model Details:

#### CNN with Torch Text (Fasttext):
* input_size = 45105
* word_vec_size = 300
* num_epochs = 5
*  window_sizes= 3, 4, 5
* n_filters = 100, 100, 100
* Test accuracy:  0.5189
  
#### Bidirectional RNN with Torch Text (Fasttext)
* input_size = 10003
* word_vec_size = 100
* hidden_size = 128
* learning_rate = 0.01
* NUM_EPOCHS=5
* optimizer = Adam
* Test Accuracy: 0.5003

#### GRU
* input_size = vocab_size
* word_vec_size = 100
* hidden_size = 128
* learning_rate = 0.001
* NUM_EPOCHS=5

#### Bert base("klue/bert-base")
* max_len = 64
* BATCH_SIZE = 16
* dropout_rate = 0.2
* num_epochs = 5
* Learning_rate =  2e-5
  
