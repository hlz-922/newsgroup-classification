# newsgroup-classification

### Project description

This project focused on classifying documents from the 20 Newsgroups dataset, a collection of English posts from Usenet newsgroups. This project aims to classify documents into six specific topics: **`comp.os.ms-windows.misc`**, **`comp.windows.x`**, **`rec.motorcycles`**, **`rec.sport.baseball`**, **`rec.sport.hockey`**, and **`sci.space`**.

### Key steps

- Use **`Pipeline`** to build an object to build a model for news classification
- The model includes a preprocessor, vectorizer, and a model
- The preprocessor includes converting the raw data into lower case, remove html and usenet info, tokenization, remove punctuation and stop words
