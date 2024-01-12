# POS-Tagging-and-Name-Entity-Recognition

## Introduction
This repository contains Python code that demonstrates the usage of the SpaCy library for natural language processing (NLP). Two specific tasks are addressed in this code:

### Task 1: Dependency Parsing and Part-of-Speech Tagging
The first part of the code showcases how to perform dependency parsing and part-of-speech tagging using SpaCy. It processes a sample sentence and provides insights into the grammatical structure, parts of speech, and their respective tags.

### Task 2: Named Entity Recognition (NER)
The second part of the code focuses on Named Entity Recognition (NER) using SpaCy. It identifies entities such as locations, organizations, and monetary values in a given sentence and prints out the recognized entities along with their labels.

## Dependencies
Ensure that you have the following Python libraries installed:

- numpy
- pandas
- seaborn
- matplotlib
- spacy

You can install these dependencies using the following command:

```bash
pip install numpy pandas seaborn matplotlib spacy
```

Additionally, SpaCy requires the English language model, which can be installed using:

```bash
python -m spacy download en_core_web_sm
```

## Usage
To run the code, execute the provided Python script. The code consists of two main tasks, each represented by separate sections:

### Task 1
This section demonstrates how to perform dependency parsing, part-of-speech tagging, and visualize the dependency tree using SpaCy. It prints out the parsed sentence, part-of-speech information for each word, and renders a dependency tree.

### Task 2
This section showcases Named Entity Recognition (NER) using SpaCy. It identifies entities in a given sentence and prints out the recognized entities along with their labels. Additionally, it renders a visualization of the recognized entities.

