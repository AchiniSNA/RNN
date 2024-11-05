# RNN Autocomplete Model

This project aims to build a Recurrent Neural Network (RNN) model that suggests autocompletions for partially typed words, a feature commonly found in applications like email clients and messaging apps.

## Project Structure

### Autocomplete Model
The model is designed to:
- Take in the beginning letters of a word (e.g., "univ").
- Predict and output the most likely completions (e.g., "university," "universal").
  
### Dataset
- **`wordlist.txt`**: This file contains 10,000 commonly used English words and will serve as the vocabulary for training the model.
  
### Implementation
Implement the RNN model using the Python `torch` library (PyTorch) to learn from word patterns and predict word completions based on partial input.
