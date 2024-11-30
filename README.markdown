# Named Entity Recognition with Small Strongly Labeled and Large Weakly Labeled Data

We provide a three stage framework:

Stage I: Domain continual pre-training.
Stage II: Noise-aware weakly supervised pre-training.
Stage III: Fine-tuning. In this code base, we actually provide basic building blocks which allow arbitrary combination of different stages. We also provide examples scripts for reproducing our results in BioMedical NER.

# Performance Benchmark

# BioMedical NER

Method (F1) BC5CDR-chem BC5CDR-disease NCBI-disease BERT 89.99 79.92
85.87 bioBERT 92.85 84.70 89.13 PubMedBERT 93.33 85.62 87.82 NEEDLE
91.38 82.57 88.53


