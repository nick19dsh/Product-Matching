# Product-Matching

After downloading the data, basic preprocessing was done which included removing null values and redundant features. Some features were modified in accordance to the task at hand.

For this problem, Word Embeddings and Sentence Transformers are used. The dataset was filtered by the product brand and features to obtain a smaller and more accurate pool of data and to reduce time for calculation. Then the description of each product of Amazon dataset was embedded into vectors using Sentence transformer. For each Flipkart product, the Cosine Similarity of the description of the product was calculated with every product of the filtered Amazon list, and the product with the highest scored was considered as the match for the Flipkart product.
