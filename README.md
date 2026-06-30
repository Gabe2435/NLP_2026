# NLP_2026: Information Retrieval & Natural Language Processing

This repository contains the notebooks, exercises, and code developed for the **Information Retrieval and Natural Language Processing** course at the University of Palermo. The repository traces the learning path from fundamental indexing techniques to more advanced NLP applications, including text generation using LLMs.

## Repository Structure

The repository is organized into two main sections: basic laboratory exercises and the final project.

### Laboratory Exercises (`IR_NLP_Class_notebooks`)
This section contains the implementations of the concepts covered in class:
* `Exercise0506.ipynb` & `ExercisePython.ipynb`: Setup notebooks and practice with Python fundamentals for text analysis.
* `InvertedIndex.ipynb`: Development of an Inverted Index, a fundamental data structure for Information Retrieval and search engines.
* `LSA_tf_idf.ipynb`: Implementation of Latent Semantic Analysis (LSA) and calculation of TF-IDF metrics for text feature extraction, weighting, and semantic retrieval.

### Final Project (`IRNLP_Project_...`)
This folder contains the final project for the exam:
* `Dataset_preprocessing.ipynb`: Data cleaning, tokenization, and dataset preparation for classification tasks.
* `ClassificationSentiment.ipynb`: Training and evaluation of models for sentiment classification.
* `ClassificationSpeaker.ipynb`: Classification task aimed at speaker identification within documents.
* `DialogueCoherence.ipynb`: Semantic analysis to evaluate the logical coherence of dialogue turns.
* `LLM_dialogueGEN...`: Experimentation for dialogue generation using Large Language Models with SFT.
* `TextRank_Project.ipynb`: Implementation of the TextRank algorithmfor keyword extraction.
* `IR_project.ipynb`: The main notebook that orchestrates the various Information Retrieval modules of the project.

## Libraries
* **Language:** Python
* **Data Management:** `pandas`, `numpy`, `scikit-learn`
* **DL & LLMs:** `nltk`, `spacy`,`gensim`,`keras`, `torch`, `unsloth`, `trl`, `transformers`
