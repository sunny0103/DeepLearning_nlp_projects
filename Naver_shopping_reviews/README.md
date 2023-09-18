### Naver shopping reviews classification
This task involves multiclass classification using online shopping review data. In this analysis, I compare three different models and employ an ensemble approach with these three models to make predictions on the test data.
Evidently, utilizing the ensemble model resulted in a higher level of accuracy compared to using a single model.

- Data source: Dacon data
#### model 
- bert 
- electra
- funnel
#### hyperparameters
- learning rate : 2e-5
- epochs : 1-3 depends on model
- seed :42 (fixed)

#### results:
- Bert 
  - Validation loss: 0.701, Accuracy: 0.701
- electra :
  - Validation loss: 0.696, Accuracy: 0.698
- Funnel
  - Validation loss: 0.697, Accuracy: 0.708
- Test result: 
  - Accuracy: 0.7084
