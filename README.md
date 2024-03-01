# Sentence-Generation-with-BeRP
This repository goes into exploring the transcripts of the Berkeley Restaurant Project (BeRP) for generating random but meaningful sentences.

## Technical Details:
- **BeRP Corpus**: The [BeRP dataset](https://github.com/wooters/berp-trans) comprises transcripts of conversations related to restaurant services in Berkeley, CA. This project utilizes the BeRP transcripts as the primary data source for building the n-gram model and generating sentences. These transcripts provide a rich and diverse collection of restaurant-related dialogue.
- **n-Gram Language Modeling**: The project implements an n-gram model modeling techniques to analyze the sequential word patterns within the transcripts, which predicts the next word in a sequence based on the preceding n-1 words. Experimenting with different n-gram sizes can offer varying levels of context dependence in the generated sentences.

## Key Files:
- `lm_model.py`: This file houses the core functionality of the trained model, which utilizes the n-gram language modeling approach and BeRP transcripts.
- `testing_ngram_lm.ipynb`: This Jupyter Notebook contains comprehensive unit tests to ensure the model's correctness across various scenarios, including edge cases.
- `test_minitrainingprovided.py`: This Python file encompasses all the unit tests used to evaluate the model's performance.
