# boolean-retrieval-system

## Overview

The Text Retrieval Engine is a project designed for processing and retrieving information from Persian books and English movie summaries. The project is divided into three main parts:

1. **Text Preprocessing:**
   - Tokenization
   - Normalization
   - Stemming
   - Stop words removal

2. **Inverted Index Creation:**
   - Utilizes the posting-dictionary concept
   - Orders items based on their repetition in documents

3. **Boolean Retrieval Model:**
   - Implements a matrix to store tokens with their presence or absence in documents
   - Allows users to input queries in a specified format for retrieval

## Usage

To use the Text Retrieval Engine, follow these steps:

1. **Data Preprocessing:**
   - Ensure your datasets are in the correct format (Persian books and English movie summaries).
   - Run the preprocessing script to tokenize, normalize, stem, and remove stop words.

2. **Inverted Index Creation:**
   - Run the script to generate the inverted index based on the processed data.

3. **Boolean Retrieval:**
   - Execute the Boolean retrieval script.
   - Enter queries in the specified format (e.g., `city+!church.taxi+!six`).
   - Receive a list of document indices where the tokens appear.

## Query Model

- `dot`: Represents logical AND.
- `!`: Represents logical NOT.
- `+`: Represents logical OR.

**Query Example:**
