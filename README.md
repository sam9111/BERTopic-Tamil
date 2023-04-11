# Topic Modelling in Tamil

This is a project that leverages c-TF-IDF and BERTopic to perform topic modeling on a corpus of Tamil documents. The project uses custom preprocessing techniques for Tamil text, as well as a custom POS tagger based on the Stanza library.

While BERTopic does not natively support Tamil language, the project uses pre-trained Tamil models from LabSE to create a custom embedding model, which is used to cluster the documents into topics.
