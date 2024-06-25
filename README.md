# Multilabel_text_classification
A multilabel text classifier is model designed to assign multiple labels to a single piece of text. This type of classifier is particularly useful for tasks where a text can belong to multiple categories simultaneously, such as in toxic comment classification, news categorization, or tagging articles with multiple topics

this dataset consist of these categories
Toxic
Non toxic 
Severe toxic
Obscene
Identity hate
Insult

first of all i applied Natural language processing technique to tokenize then remove stopwords and also remove links and hyperlinks from the dataset and used the embedded layer to convert text to vectors
In this particular model i used the deep learning framework tensorflow in which i used LSTM to train the model although its give me a handsome accuracy
