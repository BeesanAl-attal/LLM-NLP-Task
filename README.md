# LLM-NLP-Task
## Content of the Repository 
+ **.ipynb files**
  * **Task1**: contains the data preprocessing pipline, covering the first section of the task (data preprcoessing)
  * **Task2**: A logistic regrssion model, where i fited the model on the processed data retrieved from section one of the task.
  * **Task3.1**: A bi-directionl lstm model fitted on the processed data covering a part one of section three of the task.
  * **Task3.2**: A bi-directionl lstm model fitted on raw data (unprocessed) covering part two of section three of the task.
  * **Task4**: A gpt2 model, tuned using one, two, and three shot learning and applying prompt engineering practices to get more accurate results.
+ **Processed data file .plk**
  * **processed_reviews**: Contains the processed data, resulted from section one of the task.
+ **Models Weights files**
  + **logistic_regression_model**: Task2
  + **bilstm_sentiment_model.pt**: Task3.1
  + **bilstm_sentiment_model_raw.pt**: Task3.2
+ **Requirments File**
  <br>
  **Note that, all of the notebooks in this repo where executed in the same virtual enviroment with specified versions of libraries to avoid any kind of conflict**
  </br>
+ **General Notes**
  1. When you run the training loop block of code, you might get different resutls since i did not fix a seed
  2. For each trained model there is a model weights file that you can use it to load the model later and use it to predicte
  3.  All the python code are (notebooks) .ipynb to show the training epochs clearly 
    
  
