# RuDetoxEval

Repo for solution of competition [RuDetoxEval](https://codalab.lisn.upsaclay.fr/competitions/532) as a task for Homework of Statistical Natural Language Processing course @ Skoltech '21.

## Idea

The goal of competition is to make russian toxic text less toxic, saving the original meanings.

## Quick start

1. You need to store (Roberta toxic classifier) [https://huggingface.co/SkolkovoInstitute/roberta_toxicity_classifier/tree/main]
in folder Roberta_toxic

2. make a clone of repo https://github.com/skoltech-nlp/rudetoxifier and save in in folder rudetoxifier.


## Repository contents

| File or Folder | Content |
| --- | --- |
| data | folder contains datasets for classification, originally was got from (competition)[https://codalab.lisn.upsaclay.fr/competitions/532]  |
| template.ipynb | jupyter notebook contains solution and used model describtions|
| Roberta_toxic | folder to store (Roberta toxic model)[https://huggingface.co/SkolkovoInstitute/roberta_toxicity_classifier/tree/main] |
| utils.py | file with necessary functions |

## Results

As a result approach to classiy toxic words with Roberta model and drop it perform the bext according the metrics.

More details you can see in jupyter notebook with more experiment details. 

## Contacts

| **Name** | **Telegram** |
|----:|:----------:|
| Petr Sokerin | @Petr_Sokerin |
