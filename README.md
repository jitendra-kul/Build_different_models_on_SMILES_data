# Build_different_models_on_SMILES_data

The dataset includes SMILES representations and corresponding activity values. In this context, I've approached the problem as a regression task and employed three distinct methods to address it.

Firstly, I utilized fingerprint calculations, conducted hyperparameter tuning, and developed several models.

Secondly, I employed a sequential model while keeping the descriptors consistent, which in this case were fingerprints.

Lastly, for experimental purposes, I adopted an advanced architecture using PyTorch. In this approach, I utilized the BertTokenizer for SMILES and designed a model.
