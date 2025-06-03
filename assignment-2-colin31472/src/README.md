# Indicate the name of the program
Language Identification with N-gram Models
# Give a short description of the problem solved
This project implements statistical language models to solve the problem of language identification.

The letter bigram model treats each lowercase alphabetic character as a token (ignoring punctuation and other symbols), and adds start (“^”) and end (“$”) markers to capture sentence boundaries. Add‑one smoothing is applied to handle unseen letter bigrams.

The word bigram model defines a word as any contiguous sequence of letters and digits. It processes text by converting tokens to lowercase and removing punctuation, then marks sentence boundaries with `<s>` and `</s>`. Two versions are implemented:
  - One using add‑one smoothing for handling out-of-vocabulary bigrams.
  - Another using Good–Turing smoothing to better adjust probabilities for rare and unseen word bigrams, with a fallback to add‑one smoothing when singleton counts are unreliable.

The program trains separate models for English, French, and Italian using provided training data. It then evaluates each test sentence by computing the log-probability under each language model, outputs the predicted language, and compares the results against a solution file to compute accuracy.
# Give a short description on how to run your code
1. Ensure the training, test, and solution files are placed in the correct directories.
2. Run the desired Jupyter Notebook (`.ipynb`) file to train the model, perform language identification, and compute the accuracy.
3. The accuracy will be output and results will be saved to the corresponding file in the `src/Data/Output/` folder.

