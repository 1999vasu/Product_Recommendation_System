# Product_Recommendation_System
Using this code the machines will be able to recommend various products to the customers. Customer needs to specify his/her needs in
cart and the system will be able to automatically suggest him more related products.

# Model
Gensim is an open-source library for unsupervised topic modeling and natural language processing, using modern statistical 
machine learning. Gensim includes streamed parallelized implementations of fastText, word2vec and doc2vec algorithms, 
as well as latent semantic analysis (LSA, LSI, SVD), non-negative matrix factorization (NMF), latent Dirichlet allocation (LDA),
tf-idf and random projections. (~Wikipedia)

This system is trained for fastText and word2vec.

# Output

`Input`: ["Roasted Turkey", "Organic Cucumber"]

`Output`: 

    - `word2vec`: [('Organic Baby Sweet Potatoes, Microwaveable', 0.8595538139343262),
                    ('Organic Mini Cucumber', 0.8539641499519348),
                    ('Chocolate Coconut Crisps', 0.8493455648422241),
                    ('Almond Cocoa Spread', 0.8475526571273804),
                    ('Balsamic Dressing & Marinade', 0.843494713306427)]
                    
    - 'FastText`: [('Organic Roasted Turkey Breast', 0.885301947593689),
                   ('Organic English Seedless Cucumber', 0.8662012815475464),
                   ('Organic Hothouse Cucumbers', 0.8655408620834351),
                   ('Organic Roasted Sliced Chicken Breast', 0.8583692908287048),
                   ('Organic Smoked Turkey Breast', 0.8556705713272095)]
