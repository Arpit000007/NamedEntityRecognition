# Named Entity Recognition with Small Strongly Labeled and Large Weakly Labeled Data

We provide a three stage framework:

Stage I: Domain continual pre-training.
Stage II: Noise-aware weakly supervised pre-training.
Stage III: Fine-tuning. In this code base, we actually provide basic building blocks which allow arbitrary combination of different stages. We also provide examples scripts for reproducing our results in BioMedical NER.

# Performance Benchmark

# BioMedical NER

| Method(F1) | BC5CDR-chem | BC5CDR-disease | NCBI-disease |
|------------|-------------|----------------|--------------|
| BERT       | 89.99       | 79.92          | 85.87        |
| bioBERT    | 92.85       | 84.70          | 89.13        |
| PubMedBERT | 93.33       | 85.62          | 87.82        |
| NEEDLE     | 91.38       | 82.57          | 88.53        |


NEEDLE demonstrates superior performance across multiple biomedical NER datasets, outperforming prominent models like BERT, BioBERT, and PubMedBERT. By effectively leveraging a combination of strongly and weakly labeled data with noise-aware strategies, it achieves state-of-the-art F1 scores: BC5CDR-chem: 91.38, BC5CDR-disease: 82.57, and NCBI-disease: 88.53, highlighting its ability to handle noisy labels while improving domain-specific entity recognition​.
