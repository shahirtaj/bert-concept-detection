# BERT-Driven Concept Detection in Philosophical Corpora

This script accepts a corpora of text files (.txt) containing Aristotle's entries in the Stanford Encyclopedia of Philosophy as input, uses Google's Universal Sentence Encoder algorithm to embed each paragraph, and generates the proximities, or semantic textual similarity, between each paragraph and each article as output in comma-separated value files (.csv). It also generates the five paragraphs with the highest proximities to each paragraph as output in a text file (.txt).  

## TODO

Add domain-specific training after initial embeddings.

## License

Distributed under the MIT license. See ``LICENSE.md`` for more information.
