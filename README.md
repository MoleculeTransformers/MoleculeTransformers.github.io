# Molecule Transformers
Molecule Transformers is a collection of recipes for pre-training and fine-tuning molecular transformer language models, including BART, BERT, etc. This project contains the following modules:

## 1. [Enumeration-aware Molecular Transformers](https://github.com/MoleculeTransformers/enumeration-aware-molecule-transformers)
Introduces contrastive learning alongside multi-task regression, and masked language modelling as pre-training objectives to inject enumeration knowledge into pre-trained language models.

## 2. [Fine-tuning on low-data via Semi-supervised Learning](https://github.com/MoleculeTransformers/moleculenet-bert-ssl)
Replacing fully supervised fine-tuning of molecular language models with semi-supervised learning methods including pseudo-label, and deep co-training to generalize language models in low-data scenarios.

## 3. [SMILES Featurizers](https://github.com/MoleculeTransformers/smiles-featurizers)
Allows to get neural fingerprints from pre-trained language models for training downstream ML models.

## 4. [RDKit Virtual Screening Benchmarking Platform for Transformers](https://github.com/MoleculeTransformers/rdkit-benchmarking-platform-transformers)
Port of the [RDKit Virtual Screening Platform](https://github.com/rdkit/benchmarking_platform) to work with pre-trained transformer-based language models.

## 5. [SMILES Augment](https://github.com/MoleculeTransformers/smiles-augment)
Provides different stochastic and interpolation oriented SMILES augmentation mechanisms to augment SMILES-based training datasets.
