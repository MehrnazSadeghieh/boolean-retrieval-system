# boolean-retrieval-system

## Overview

The Boolean Retrieval System is a project designed for processing and retrieving information from Persian books and English movie summaries. The project is divided into three main parts:

1. **Text Preprocessing:**
   - Tokenization
   - Normalization
   - Stemming
   - Stop words removal

2. **Inverted Index Creation:**
   - Utilizes the posting-dictionary concept
   - Orders items based on their repetition in documents

3. **Boolean Retrieval Model:**
   - Implements a matrix to store tokens with their binary representation in documents
   - Allows users to input queries in a specified format for retrieval
  
## Datasets

The required datasets for this project are available, and you can download them directly in Google Colab. The links to the datasets are provided in the notebook

## Usage

To use the Boolean Retrieval System, follow these steps:

1. **Data Preprocessing:**
   - Ensure your datasets are in the correct format (Persian books and English movie summaries).
   - Run the preprocessing script to tokenize, normalize, stem, and remove stop words.

2. **Inverted Index Creation:**
   - Run the script to generate the inverted index based on the processed data.

3. **Boolean Retrieval:**
   - Execute the Boolean Retrieval script.
   - Enter queries in the specified format
   - Receive a list of document indices where the tokens appear.

## Query Model

- `dot`: Represents logical AND.
- `!`: Represents logical NOT.
- `+`: Represents logical OR.

### Query Example
`city+!church.taxi+!six`

## Google Colab

This project is implemented in Google Colab
Open the notebook in Google Colab by clicking on the following link:  https://colab.research.google.com/drive/1eJrS0XcQOIAbsIolL1CVe2lNnVUuZtB0#scrollTo=p3WoHUaUKQo1
