Application and implementation of People China Daily text automatic summarization system based on word2vec algorithm

- Trained a 300-dimensional Word2Vec model using Gensim on a Chinese news corpus.
- Adopted the SIF(Smooth Inverse Frequency)algorithm to apply PCA, reducing word vector dimensions and obtaining superior sentence embeddings.
- Calculated the cosine similarity between sentences and the title/article as a weighted score for summarization.Refined these scores with KNN smoothing and selected the top-k sentences based on rank.
