# N-Gram Language Model Evaluation

This repository contains the implementation and evaluation of N-Gram Language Models (Unigrams, Bigrams, and Trigrams) for a given corpus. The models are evaluated using both intrinsic and extrinsic methods to assess their performance.

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Evaluation](#evaluation)
  - [Intrinsic Evaluation](#intrinsic-evaluation)
  - [Extrinsic Evaluation](#extrinsic-evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Overview

This project involves the creation of N-Gram models (Unigrams, Bigrams, and Trigrams) and their evaluation using two primary methods:

### Task 1 - Creation of N-Gram Models:
1. **Unigrams**: A unigram model calculates the probability of each word in the corpus independently.
2. **Bigrams**: A bigram model calculates the probability of a word given the previous word.
3. **Trigrams**: A trigram model calculates the probability of a word given the previous two words.

### Task 2 - Intrinsic Evaluation:
- **Perplexity**: Measures the model's ability to predict a test dataset by calculating the inverse probability of test data normalized by the number of words.

### Task 3 - Extrinsic Evaluation:
- The models are evaluated using an extrinsic task, such as a classification task, and evaluated using metrics like accuracy, precision, recall, and F1-score.

### Language Models Implemented:
- **Unigrams**: Single word probabilities based on frequency in the corpus.
- **Bigrams**: Two-word sequence probabilities.
- **Trigrams**: Three-word sequence probabilities.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/ngram-language-model.git
   cd ngram-language-model
