# <p align=center>Classification of Scientific Articles Sentences Embeddings generated by Contrastive Learning</p>

This repo has code and data for the paper titled Classification of Scientific Articles Sentences Embeddings generated by Contrastive Learning

## Introduction

All codes are in Jupyter Notebook format.

## Directory Strucutre

Directory Dataset holds the training, validation and testing sets of all three datasets: CSAbstruct, PMC-Sents-FULL and PubMed_RCT.

1. The base directory referes to the datasets: CSAbstruct, PMC-Sents-FULL or PubMed_RCT.
2. Each dataset directory has two sub-directories to the correspondent model: MiniLM or SciBERT.
3. Each model's directory has a BI-ENCODER and a CLASSIFIER directory.
4. In each model's directory there is a TRAIN and TEST Jupyter Notebook file.
  4.1 The results presented in the paper are in the TEST Jupyter Notebook files.
  4.2 For all MiniLM CLASSIFIER directories there is a single file that contains both train and test codes.
