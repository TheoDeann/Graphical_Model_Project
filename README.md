# Graphical_Model_Project
the final project of graphical model in centrale supélec 2023

#Abstract
This project provides a gentle discussion of two popular graph neural network (GNN) models, Graph Attention Network (GAT) and Graph Isomorphism Network (GIN), along with a numerical representation and pros/cons analysis. We implement both networks on two datasets, Citeseer and Protein in TUDataset, for node and graph classification tasks respectively, and report accuracy on both train and test sets. We use PyTorch Geometric to design the network architectures and implement GAT on Citeseer from scratch. We find that GAT is better suited for tasks where local structure is important, while GIN is better suited for tasks where global structure is important. 
