# FactorGraphNeuralNet
The Factor Graph Neural Network model for Interpretable Deep Learning

While deep learning has achieved great success in many fields, one common criticism
about deep learning is its lack of interpretability. In most cases, the hidden
units in a deep neural network do not have a clear semantic meaning or correspond
to any physical entities. However, model interpretability and explainability are
crucial in many biomedical applications. To address this challenge, we developed
the Factor Graph Neural Network model that is interpretable and predictable by
combining probabilistic graphical models with deep learning. We directly encode
biological knowledge such as Gene Ontology as a factor graph into the model
architecture, making the model transparent and interpretable. Furthermore, we
devised an attention mechanism that can capture multi-scale hierarchical interactions
among biological entities such as genes and Gene Ontology terms. With
parameter sharing mechanism, the unrolled Factor Graph Neural Network model
can be trained with stochastic depth and generalize well. We applied our model
to two cancer genomic datasets to predict target clinical variables and achieved
better results than other traditional machine learning and deep learning models.
Our model can also be used for gene set enrichment analysis and selecting Gene
Ontology terms that are important to target clinical variables.
