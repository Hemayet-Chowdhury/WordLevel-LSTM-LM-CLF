# WordLevel-LSTM-LM-CLF
Word Level LSTM Language Model and Classifier for Authorship Attribution on Bengali WikiPedia Data

DataSet Link - Wikipedia dataset : https://drive.google.com/file/d/1MoyTCHL9zqt2UF_iU2k4z0i_AVvls0ry/view?usp=sharing

This project trains an ASGD Weight Dropped LSTM Language Model on a Word Level. (We extend the wok on a subword level in another repo)

Uses the 3 layer Deep Language Model instead of a single word embedding representation.

Intuition : Language Model captures the hidden semantic information of the Bengali Language itself.

Transfers the knowledge of the Language Model to the LSTM classifier.
