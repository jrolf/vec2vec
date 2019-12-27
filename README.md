# vec2vec
Python ML Module for Linear and Non-Linear Translation of 1D Vector Arrays

### Value of Embeddings and 1D Vectors in Machine Learning 
Many modern machine learning pipelines involve the use of embeddings, principal components, or other locational representation that exists in vector space. In these cases, the coordinates of an entity or observation may be defined as a 1-dimensional array with length equal to the number of dimensions or components being represented by the underlying vector space. In the case of word vectors (as produced by word2vec), a single vector (for a single word) may consist of 200 latent embeddings that are represented as 200 floating-point values in a numpy array. None of these numeric values may have an explicit or easy-to-understand interpretation, but the collection of the values together are a quantitative representation of the underlying MEANING of a word. A word's numeric embedding can then be leveraged in machine learning operations to determine the likelihood of a word given certain other words in a sentence.

### Conditioning Hyperspace
Embeddings can have powerful inferential properties. A strong embedding model doesn't just fit entities to a pre-defined hyperspace, but simultaneously fits entity coordinates AND the underlying hyperspace geometry at the same time. The consequence of this is that the resulting model is capable of operations far more powerful than entity similarity calculations. 

A well-conditioned hyperspace will enable coherent analogy formation. That is, the hyperspace will be structured in such a way that it doesn't just inform you which entities are most similar, but the direction that you travel in this hyperspace has a unique meaning that can be transposed or projected to a different origin, while maintaining the same relational meaning. In so doing, it is possible to make analogies between entities and to infer differences and relationships between entities 

### The Challenge of Vector Translation
TODO



