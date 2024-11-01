# Named Entity Recognition with BERT
This project implements a Named Entity Recognition (NER) system using a fine-tuned BERT model.

## Features

- Utilizes the BERT architecture for token classification.
- Pre-trained model available for improved prediction accuracy.
- Supports inference on custom text inputs.

## Instructions

1. Run the notebook `Named-Entity-Recognition-with-BERT.ipynb`.

2. The model will be saved as `/content/ner_model.pth`. 

3. Run inference with this model.

This implementation is compared with the `AutoModelForTokenClassification.from_pretrained('dbmdz/bert-large-cased-finetuned-conll03-english')` model for performance evaluation.
