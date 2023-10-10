# Build-different-models-on-SMILES-data

The dataset includes SMILES representations and corresponding activity values. In this context, I've approached the problem as a regression task and employed three distinct methods to address it.

Firstly in task1, I utilized fingerprint calculations, conducted hyperparameter tuning, and developed several models.

Secondly in task2, I employed a sequential model while keeping the descriptors consistent, which in this case were fingerprints.

Third in task3, for experimental purposes, I adopted an advanced architecture using PyTorch. In this approach, I utilized the BertTokenizer for SMILES and designed a model.

Finally in task4, I applied a Graph Neural Network using the Chemprop module. In this scenario, I directly used the SMILES as input during the training process
