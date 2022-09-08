# Quick Label

Use hugging-face and koaning/bulk to train a classifier. 

Steps 
1) Find the most similar model from the model library
2) Generate embeddings and load into bulk 
3) Label dataset
4) Use labelled dataset to finetune hugging face model 

In industry you could then repeat this cycle with the new embeddings.
