# Biology and Deep Learning, especially Transformers
List of deep learning related to biology and some learning resources.

# Table of Contents



# LLMs and Biology

[AlphaFold v2](https://github.com/google-deepmind/alphafold) An attention-based deep learning algorithm released by Google's DeepMind to predict protein structures.

[CpGPT](https://www.biorxiv.org/content/10.1101/2024.10.24.619766v1) CpGPT was created as a foundation model for DNA Methylation trained using over 100,000 samples from diverse tissues and conditions. Finetuned models for aging were supposed to be released on Python's pyaging and R's methyCYPHER. As of November 4, 2024, they had not been released.

[DNABERT](https://academic.oup.com/bioinformatics/article/37/15/2112/6128680) The model predicts regulatory and seqeunce motifs from DNA seqeunces. When examining variants, the highest attention scores were found variants of interest to functional biology. The model was updated to [DNABERT-2](https://github.com/MAGICS-LAB/DNABERT_2).

[ESM2](https://github.com/facebookresearch/esm) A transformer model from Meta that is able to design protein structure and was shown to be able to go beyond natural proteins in this [paper](https://www.biorxiv.org/content/10.1101/2022.12.21.521521v1). 

[GeneGPT](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC10153281/) An LLM approach, which uses National Center for Biotechnology Information (NCBI) APIs to address prompts about biomedical questions. The paper reports results from the gene turing tests.

[MethylBert](https://github.com/CompEpigen/methylbert?tab=readme-ov-file) A transformer model developed to predict the tumor fraction from DNA methylation. Tumor purity is inferred using a maximum likelihood estimate.

[GOProFormer](https://pubmed.ncbi.nlm.nih.gov/36421723/) Combines seqeunce and graph transformers to predict protein functions using GO terms and the protein sequence. The input is the protein sequence data. 

[ProtGPT2](https://pubmed.ncbi.nlm.nih.gov/35896542/) A decoder only transformer model that can be used to produce <i>de novo</i> protein designs while maintaining conserving features of natural proteins. 

# LLMs and Chemistry



# LLMs and Scientific literature

[BioBERT](https://github.com/dmis-lab/biobert) Developed by Google, BioBERT is a multilingual model re-trained on a large corpus of biomedical texts, including abstracts, full-text articles, and other scientific publications. The training dataset includes papers from PubMed Central, NCBI's bioinformatics database.

[BioMedBert](https://arxiv.org/abs/2007.15779) A BERT model trainined on Pubmed abstracts and PubMed Central articles. It was originally referred to as PubMedBERT and is on HuggingFace [here](https://huggingface.co/microsoft/BiomedNLP-BiomedBERT-base-uncased-abstract-fulltext).

[SciBERT](https://github.com/allenai/scibert) Also developed by Google, SciBERT is another multilingual model that was trained on a large corpus of biomedical texts, including research articles, reviews, and abstracts. Like BioBERT, it uses       data from PubMed Central and other sources to train its language model. 

# Learning resources

 [SMILES](https://en.wikipedia.org/wiki/Simplified_Molecular_Input_Line_Entry_System#cite_note-Weininger-1988-1) Simplified Molecular Input Line Entry System or SMILES is a line notation for chemical structures which allows for molecular structure data to be used by deep learning architectures such as LLMs. 

## Scientific Papers with LLM focus for background and more
[Attention is All You Need](https://arxiv.org/abs/1706.03762)This is the initial paper that helped spawn the attention-based methodology that spawned the transformer model revolution.

[Scalable MatMul-free Language Modeling](https://arxiv.org/abs/2406.02528v1) An alternative model where matmul functions are replaced by ternary calculations, e.g. {-1,0,1}

## Blogs and Tutorials
[Kaggle Introduction](https://www.kaggle.com/code/alejopaullier/introduction-to-transformers)  One introduction to transformers on kaggle. There are several transformer related posts on Kaggle worth a read.

[Benjamin Warner Blog](https://benjaminwarner.dev/)  There is a 2 part post about creating a transformer from scratch at https://benjaminwarner.dev/2023/07/28/rest-of-the-transformer and https://benjaminwarner.dev/2023/07/01/attention-mechanism.

[Mr Logic Build a Chatbot](https://www.youtube.com/watch?v=7TFuBVX2NIs&t=133s) The author provides a explanation of transformer architecture and a how-to for building a transformer-based chatbot.

[Tien Tran Understanding Attention - a Kaggle notebook](https://www.kaggle.com/code/tientd95/understanding-attention-in-neural-network/notebook) The notebook goes through transformers and uses the Cornell Movie Dialogs dataset for demonstation.

