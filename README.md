# Named Entity Recognition Model with Context Specific Training Dataset

This script shows how to implement named entity recognition model via neural network on a bunch of article text data. The articles come from different Australian sources,
mainly from construction report websites, hence have a specific context. To improve the model, we will need to feed it with train data to capture the context.
We will introduce several specifications: importing spacy ner model and adding each of the label separately, then adding all labels altogether, and then
using the Stanford NER model, which is supposed to outperform all models.
