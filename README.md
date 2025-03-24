# Smart Tabular QA System

## Overview  
The **Smart Tabular QA System** is an advanced question-answering system designed to extract relevant information from structured table data. By leveraging **Natural Language Processing (NLP)**, **word embeddings**, **vector comparison**, and **sentence transformers**, the system accurately processes user queries and retrieves the most relevant answers from tabular datasets.

## Features  
- ✅ Supports **natural language queries** over structured table data  
- ✅ **Preprocesses text** by tokenization, lemmatization, and stop-word removal  
- ✅ Converts text into **vector representations** using word embeddings  
- ✅ Uses **sentence transformers** to enhance query understanding  
- ✅ **Compares vectors** to find the best-matching answer  
- ✅ Handles **missing values, outliers, and feature scaling** for better accuracy  
- ✅ **Optimized performance** for quick and efficient responses  

## Approach & Workflow  

### 1. Data Preprocessing  
- Handles **missing values** (mode for categorical, median for numerical)  
- Removes **outliers** using the **Interquartile Range (IQR) method**  
- Scales numerical features using **MinMaxScaler**  

### 2. Text Processing (NLP)  
- Tokenization and **lemmatization** for better text normalization  
- Removal of **stop words** to retain essential information  
- Conversion of processed text into **word embeddings**  

### 3. Vectorization & Similarity Matching  
- Uses **TF-IDF** and **word embeddings** to convert text into numerical form  
- Applies **sentence transformers** for better query understanding  
- Computes **cosine similarity** between the user query and table data to find the best match  

### 4. Answer Retrieval  
- Identifies the most relevant table entry based on similarity scores  
- Returns the **best-matching answer** to the user query  



