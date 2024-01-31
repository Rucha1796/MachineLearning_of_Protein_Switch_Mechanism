Ligands can bind at specific protein locations, inducing conformational changes such as those
involving secondary structure. Identifying the possible switches from sequence, including
homology, is an important ongoing area of research. We attempt to predict whether a protein
residue is a switch, from sequences in protein using machine learning, specifically a logistic
regression, linear SVM, and random forest. Our sequence descriptors included amino acid
residue type, six and twenty-term sequence entropy, Lobanov-Galzitskaya’s residue disorder
propensity, Vkabat (Variability for predictions from a sequence of the helix, sheet, and other),
IsUnstruct, Secondary structure predicting algorithms and possible combinations of the
sequence descriptors. We leveraged ROC curves and AUC values to analyze our results. We
found AUC values slightly higher for the Random Forest with the combination of secondary
structure prediction algorithms as our feature set. In the future, we hope to expand our feature
set and combine secondary structure predicting algorithms with Entropy values as our feature
sets. In addition, we hope to explore more sophisticated regression models like non-linear
SVM and deep learning.
