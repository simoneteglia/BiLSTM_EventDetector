# BiLSTM_EventDetector

This is a BiLSTM model that I created for the first homework of the 2023 NLP master course at Sapienza with instructor Roberto Navigli.
The model takes in input a sentence and returns a tag for each word among those ones ['O','B-SCENARIO','B-CHANGE','B-ACTION','B-SENTIMENT', 'I-CHANGE', 'B-POSSESSION', 'I-ACTION', 'I-SENTIMENT', 'I-SCENARIO', 'I-POSSESSION']

## Performances
Training, validation and test were performed using a dataset given during the class.  
Macro F1-Score: 0.72136   
Macro Precision:  0.71571   
Micro Precision:  0.94911   
