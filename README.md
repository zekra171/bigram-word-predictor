# Bigram Word Predictor using NLTK

This project implements a simple **Bigram Word Predictor** using the [NLTK](https://www.nltk.org/) library in Python.  
It predicts the next word in a sentence based on the frequency of word pairs (bigrams) in a given training text.

---

## Features
- Tokenizes text and generates bigrams.
- Trains a simple frequency-based bigram language model.
- Predicts the most likely next word given a previous word.
- Can suggest multiple possible next words with probabilities.

---

##  Requirements

Make sure you have **Python 3.7+** installed.

Install the required libraries:
```bash
pip install nltk

```
## Download the NLTK resources (run once)
```
import nltk
nltk.download('punkt')
```
## How to Run

1 Clone this repository
```
git clone https://github.com/YourUsername/YourRepoName.git
cd YourRepoName
```
2 Run the script
```
python bigram_predictor.py
```
3 Follow the prompts
You will be asked to enter a starting word, and the program will suggest the most probable next word(s).

Input
---
A starting word (string) to base the prediction on.
Example:
```
Enter a word: I
```
 Output
 ---
The predicted next word(s) with probabilities (if implemented).

Example:
```
Predicted next word: am
Other suggestions: ['have', 'was']
```
📌 Example Usage
---
Training Text:
```
I am happy today because I am learning NLP.
I have a meeting today.
```
Prediction:
```
Enter a word: I
Predicted next word: am
Other suggestions: ['have']
```

تحرير




