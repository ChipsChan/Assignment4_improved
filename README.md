# O. Henry Short Stories Corpus
## Description
This corpus consists of 12 short stories written by the American author O. Henry, renowned for his wit, wordplay, and surprise endings. The stories were selected for their literary significance and the variety in themes and styles they present.

## Target Audience and Intended Use
The corpus is intended for literary scholars, students, and natural language processing (NLP) enthusiasts interested in analyzing O. Henry's narrative style and language use. It can be used for educational purposes, literary analysis, or as a dataset for NLP tasks like text analysis, sentiment analysis, and more.

## Text Selection Criteria
The short stories were carefully chosen to represent a broad range of O. Henry's work. Selection criteria included the popularity of the stories, their critical acclaim, and the diversity in themes and narrative techniques.

## Data Collection Process
The texts of the short stories were collected from https://www.gutenberg.org/ebooks/author/634. Each story was then downloaded as a separate text file in the corpus.

## Cleaning and Preprocessing
The following preprocessing steps were undertaken:

1. **Text Cleaning**: Removal of extraneous text and formatting to ensure clean, consistent text data.
2. **Tokenization**: Breaking down the text into individual words and symbols.
3. **Lemmatization**: Converting words to their base or dictionary form.
4. **POS Tagging**: Identifying parts of speech for each word in the text.

## Annotations and Tools
For the NLP annotations, the following tools were used:

- **spaCy**: An open-source software library for advanced natural language processing, used for tokenization, lemmatization, and POS tagging.
- **Custom Python Scripts**: For additional data handling and processing.

## Corpus Format
The corpus files are in two formats:

- **Text Files**: Each story is stored as an individual '.txt' file.
- **CSV File**: The processed corpus data, including annotations, are compiled into a single '.csv' file. The CSV columns are as follows:
  - 'Filename': Name of the original text file.
  - 'Title': Title of the story.
  - 'Document': Original text of the story.
  - 'Tokens': Tokenized text.
  - 'Lemmas': Lemmatized text.
  - 'POS': Parts of speech.
