# Machine-Learning-on-Drug-Solubility
Using multiple machine learning algorithms to generate the best predicitive regression model on the degree of solubility of a chemical compound given its molecular formula. 

The training data is provided in the file listed as solubility_train.fp, this has the chemical structure in SMILES format, followed by the Solubility in log(S) values, and then the binary features representation in traditional MACCS fingerprints.

For more information on each format see below:
SMILES format: http://opensmiles.org/opensmiles.html
MACCS format: http://www.dalkescientific.com/writings/NBN/fingerprints.html

The testing data is provided in the file listed as solubility_predict.fp which only has the chemical structure and the MACCS fingerprints. The goal is to evaluate which model has the best predictive capability to the true solubility values.

For this machine learning task, I used a variety of algorithms in the Python Package sklearn, more information can be found here: https://scikit-learn.org/stable/
