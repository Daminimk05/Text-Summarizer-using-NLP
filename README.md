# Natural Language Processing Based Text Summarizer

## Intelligent Language Processing Project

## Project Description

The Natural Language Processing (NLP) Based Text Summarizer is an extractive summarization system designed to generate concise summaries from large textual inputs. The system identifies the most relevant sentences in a given paragraph by analyzing word frequency and sentence importance.

The project is implemented using Python and the Natural Language Toolkit (NLTK). An interactive user interface is developed using Gradio, allowing users to input text and instantly receive a summarized version.

This project demonstrates the practical application of Natural Language Processing techniques, including tokenization, stopword removal, frequency analysis, and sentence scoring.

---

## Aim

To design and develop an NLP-based text summarization system that can process long textual content and generate a concise summary by extracting the most meaningful sentences.

---

## Working Principle

1. The user enters a block of text into the system.
2. The text undergoes preprocessing, including cleaning and normalization.
3. The text is tokenized into sentences and words.
4. Stopwords are removed to retain meaningful words.
5. Word frequencies are calculated and normalized.
6. Sentences are scored based on important word occurrences.
7. The top three highest-scoring sentences are selected.
8. These sentences are combined to generate the final summary.

---

## Methodology

### 1. Text Preprocessing
- Removal of special characters using Regular Expressions
- Conversion to lowercase
- Removal of extra spaces
- Sentence and word tokenization

### 2. Stopword Removal and Frequency Calculation
- Removal of common English stopwords using NLTK
- Creation of a word frequency table
- Normalization of frequency values

### 3. Sentence Scoring
- Each sentence is evaluated based on the sum of normalized word frequencies
- Sentences longer than 30 words are ignored to reduce redundancy

### 4. Summary Generation
- Top three ranked sentences are selected
- Sentences are combined to form the final extractive summary

---

## Technologies Used

- Python  
- NLTK (Natural Language Toolkit)  
- Gradio  
- Regular Expressions (Regex)  
- Google Colab  

---

---

## Project Screenshots

### Input Interface
<p align="center">
  <img src="images/Text Summarizer UI (1).png" width="600">
</p>

### Generated Summary
<p align="center">
  <img src="images/Text Summarizer UI (2).png" width="600">
</p>

---

## Skills and Concepts Applied

- Natural Language Processing  
- Text Preprocessing  
- Tokenization  
- Stopword Removal  
- Frequency Analysis  
- Extractive Summarization  
- UI Development using Gradio  

---

## Applications

- Summarizing news articles  
- Creating concise academic notes  
- Extracting highlights from research papers  
- Reducing long documents into quick summaries  

---

## Future Enhancements

- Implementation of Abstractive Summarization  
- Integration with advanced NLP models  
- Multi-language summarization support  
- Web-based deployment  

---

## Author

Damini M K  
Intelligent Language Processing Project  
