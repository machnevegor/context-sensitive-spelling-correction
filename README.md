# **Context-Sensitive Spelling Correction**

| Name         | Innomail                       | Group     |
| ------------ | ------------------------------ | --------- |
| Egor Machnev | e.machnev@innopolis.university | B22-AI-02 |

## **Overview**

This project implements a context-sensitive spelling corrector that improves
upon traditional spelling correction by considering the surrounding words in a
sentence. Unlike basic spell checkers, which rely only on word-level edits, this
model leverages N-grams and probabilistic language modeling to determine the
most likely corrections based on context.

## **How It Works**

1. Takes a sentence as input.
2. Identifies and corrects spelling mistakes while maintaining **grammatical
   correctness**.
3. Uses **bi-grams and tri-grams** to evaluate the probability of word of word
   substitutions in a given context.
4. Uses **Beam Search** to efficiently find the most likely corrections.
5. Incorporates a **pretrained vocabulary** to minimize unnecessary corrections.

## **Usage**

To explore the implementation, open the interactive Jupyter Notebook:

📌 **Jump to [Notebook](./notebook.ipynb)**
