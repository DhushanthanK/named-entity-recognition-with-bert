# Named Entity Recognition with BERT

A PyTorch-based implementation of a Named Entity Recognition (NER) model using BERT and the CoNLL-2003 dataset. This project leverages Hugging Face Transformers for token classification to identify entities such as persons, locations, and organizations.

## Features
- BERT-based NER model fine-tuned on the CoNLL-2003 dataset.
- Efficient training with early stopping and dynamic learning rate scheduling.
- Performance evaluation using precision, recall, and F1 scores via SeqEval.

## Instructions

1. Run the notebook `Named-Entity-Recognition-with-BERT.ipynb`.

2. The model will be saved as `/content/ner_model.pth`. 

3. Run inference with this model.

This implementation is compared with the `AutoModelForTokenClassification.from_pretrained('dbmdz/bert-large-cased-finetuned-conll03-english')` model for performance evaluation.
