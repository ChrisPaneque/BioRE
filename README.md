# BioREx
This repository is part of the development of the following Master Thesis: Relation Extraction between Biomedical Entities from Scientific Texts.
# Summary
This work proposes a BioRE model based on the state-of-the-art, BioBert, which was fine-tuned with a dataset specifically adapted for this task. Our model is composed of two classifiers created from representations on biomedical data in to perform intra sentence relation classification between Genes-Diseases, Chemical-Disease and Chemicals-Genes. A web platform capable of extracting relations from biomedical text has been also created based on these classifiers. The BioRE system has been evaluated showing a F1 score of 82.37, 86.74 and 69.1 to classify Genes-Diseases, Chemical-Disease and Chemicals-Genes, respectively.
# Requirements
All the system procedures were regsitered as python notebooks for It to be easily replicable and oriented to perform predictions. The Requirements file contains all the necessary libraries.
# Folder description
 # CDR_TFIDF_Model
 Contains the model trained on CDR Dataset using TFIDF for vectorization.
 # Chemprot_TFIDF_Model
 Contains the model trained on Chemprot Dataset using TFIDF for vectorization.
 # CDR_BioBert_Model
 Contains the model trained on CDR Dataset using BioBERT for word embedding.
 # Datasets
 Contains all the datasets used in the system development.
 # Predicting
 Contains Python notebooks with examples on performing prediction on new text.
 # Preprocessing 
 Contains Python notebooks with all the preprocessing performed to the CDR Dataset.
# The Fine-tuned on GAD Dataset BioBert model can be found at https://huggingface.co/ChrisUPM/BioBERT_Re_trained. It can be consumed using Huggingface's Transformers.
# A web plattform for performing BioRE is being deployed and will be available soon
