# Topic-Modelling-Using-LDA

# Brief introduction to LDA(Latent Dirichlet Allocation)
In LDA, a particular document(review in the case of this project) can be represented as a probability distribution of words. The topics are chosen based on the Dirichlet distribution. The documents with similar topics have the same group of words.

# About
This is a small project that tries to seperate the reviews of a phone model from an e-commerce website into different topics. The goal is to see which topics the reviews belong to most and to later see if changes are needed relating to certain things.

# Methodology
- The dataset was downloaded from Kaggle.
- Only the reviews column of the dataset is used as this is for topic modelling.
- Text Preprocessing is done using CountVectorizer and stopwords are removed.
- Latent Dirichelt Allocation is then applied on the result of the CountVectorizer step which is a matrix of the reviews and the different words that are present.
- The topics are later differentiated and conclusions are drawn from them.

# Screenshot of the most appearing topics in the reviews
![LDA_topics](https://user-images.githubusercontent.com/66258607/120754287-12d24300-c52a-11eb-9b1f-8e072b5288ec.PNG)
 
 # Conclusion
 Based on this, the manufacturer or the seller must look to make significant improvements to make sure they reduce the negative reviews.
