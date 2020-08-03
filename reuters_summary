# Text Classification on Reuters-21578

The commented code is provided separately.
It was simply carried out by following __steps__:

- Download the corpus
- Parse documents for processing
- Determine a set of topics
- Create a training set composing with *tf-idf* vectorised documents and corresponding labels
  (*Note, in order to increase the effectiveness of the classifier, we assigned only a single class label to each document.*)
- Train a *SVM* classifier by using Scikit-learn
- Result and further improvement solution

This classifier turns out the accuracy of __0.84__.
It could be improved in several ways:
- Refine the input documents by applying *stopwords*, *stemmer* and *lemmatizer* on preprocessing step.
- Refine input features, for instance applying *Word2Vec* to vectorise documents, *LDA* for dimension reduction.
- Perform *Grid Search Cross-Validation* on training step to optimise parameters for the classifier.
- Implement hybrid deep learning models (e.g., attention, *LSTM*, *BERT*)
