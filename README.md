# ATIS_dataset_NER_task
We employed below steps:

1. At first we implemented a approach for making a function to manually preprocess the data for NER.
2. Manually tokenize the sentence by splitting spaces.
3. After getting the preprocessed train data, created token and slot label vocabularies. Created token and slot label tokenizers.
4. Fit tokenizerson the vocubularies.
5. Convert sentences and slot labels to sequences of IDs
6. Convert slot labels to a one-hot encoded format, ensuring the index does not go out of bounds

After defining the model and fitting ner_model, here I have used Bi-LSTm as my main Deep Learning Architecture.
- Evaluate the model on the test data
- Flatten the predictions and true labels, Initialize LabelEncoder and created the classification report
- Finally extract return date and time funtion





   
