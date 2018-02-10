# Intro to Natural Language Processing Techniques

By the end of this lesson, you will be able to identify and discuss advanced NLP techniques will have been introduced to the libraries handling those. You should be able to:

- Use `spacy` to identify parts of speech and extract named entities 
- Use `textblob` to do the following sentiment analysis tasks:
    - Identify the sentiment of a piece of text
    - Identify the objectivity of a piece of text
- Use `sklearn` and Latent Dirichlet Allocation to create "topics" across a corpus of documents

Before you begin, please run the following three lines on your command line:

```python
conda install wikipedia
python -m textblob.download_corpora
python -m spacy download en
```

This will fetch the corpora needed for `textblob` and `spacy` as well as install the `wikipedia` library, which we will use for examples in this section.
