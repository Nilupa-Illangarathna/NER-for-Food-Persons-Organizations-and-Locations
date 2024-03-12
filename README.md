# Named Entity Recognition (NER) Extraction Models

[![Hugging Face](https://img.shields.io/badge/huggingface-transformers-blue)](https://huggingface.co/)
[![Python](https://img.shields.io/badge/language-python-brightgreen)](https://www.python.org/)

This repository contains Python scripts to extract named entities from text using pre-trained NER models. Two types of entities are targeted: foods and persons, organizations, and locations.

## Models Used
- **Food NER Model**: Utilizes the FoodBaseBERT model from Hugging Face's Transformers library to extract food-related entities.
- **Persons, Organizations, Locations NER Model**: Utilizes the Babelscape multilingual NER model to extract entities related to persons, organizations, and locations.

## Data
The repository includes the following data files:
- `Foods words set.txt`: A text file containing a set of food-related words used for entity extraction in the food NER code.
- Sample text files used for testing the NER extraction scripts.

## Usage
1. **Food NER Code**: Run the `food_ner_code.ipynb` notebook to extract food entities from text using the FoodBaseBERT model.
2. **Persons, Organizations, Locations NER Code**: Run the `persons_orgs_locs_ner_code.ipynb` notebook to extract entities related to persons, organizations, and locations using the Babelscape multilingual NER model.
