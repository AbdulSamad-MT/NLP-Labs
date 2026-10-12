# LAB6

## Tasks done in this lab
- Followed the Yelp reviews example (TF-IDF + a small PyTorch network)
- Trained a Word2Vec model (vector size 200, window 5, skip-gram) on the training reviews
- Turned every review into one vector by averaging its word vectors
- Built a new network 200 -> 128 -> 64 -> 32 -> 1 with ReLU
- Trained it for 15 epochs (BCEWithLogitsLoss, Adam, lr 0.001) and checked the test accuracy
