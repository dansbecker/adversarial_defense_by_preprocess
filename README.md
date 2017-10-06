This is a TensorFlow model submitted to Kaggle's [NIPS 2017: Defense Against Adversarial Attack](https://www.kaggle.com/c/nips-2017-defense-against-adversarial-attack) competition.  

It takes a model trained against adversarial examples, and attempts to make that model more robust with by ensembling predictions coming from various preprocessing steps (e.g. zooming, brightening, horizontal flipping).

Must run download_checkpoints.sh to get pretrained model.
