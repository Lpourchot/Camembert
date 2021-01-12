# Camembert
NLP model : Camembert (Bert model for french) fine tuned for sentiment analysis.

As I did not find relevant french dataset for sentiment analysis, I downloaded an english version for a translation to french.
The original Camenbert has been tuned with the translated dataset and has reached near 90% of accuracy on test dataset. Not too bad :-)
The Dataset has been limited with short sentences (2000 rows) to avoid a too long training (without GPU)

Congrats :

For the library :
https://huggingface.co

For fine tuning :
https://github.com/abhimishra91/transformers-tutorials/blob/master/transformers_multi_label_classification.ipynb

For Camembert model :
https://camembert-model.fr/

CamemBERT was trained and evaluated by Louis Martin, Benjamin Muller, Pedro Javier Ortiz Suárez, Yoann Dupont, Laurent Romary, Éric Villemonte de la Clergerie, Djamé Seddah and Benoît Sagot.
