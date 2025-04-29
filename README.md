# fever-adversarial-nli

Project developed for the course of "Multilingual Natural Language Processing" during the MSc in Artificial Intelligence and Robotics at Sapienza University of Rome, A.Y. 2023-2024.

## Summary

Implementation of many approaches to generate augmented samples starting from a subset of NLI Style FEVER dataset which was enriched with WSD (Word Sense Disambiguation) and SRL (Semantic Role Labeling) informations ([FEVER](https://fever.ai/dataset/fever.html) , [NLI Style FEVER](https://github.com/easonnie/combine-FEVER-NSMN/blob/master/other_resources/nli_fever.md), [Semantically-augmented FEVER for NLI](https://huggingface.co/datasets/tommasobonomo/sem_augmented_fever_nli)). The proposed approaches exploits the WSD and SRL labels in different ways to build new samples which are as sound as possible. 

The produced augmented dataset is available [here](https://huggingface.co/datasets/Matteo-Pannacci/mnlp_adversarial_train_set).

Implementations of baselines models and transformer-based model (based on [Distil-BERT](https://huggingface.co/docs/transformers/model_doc/distilbert)) using the original NLI Style FEVER and the augmented dataset with on both the NLI Style FEVER test subset and the [Adversarial FEVER for NLI test set](https://huggingface.co/datasets/iperbole/adversarial_fever_nli).
