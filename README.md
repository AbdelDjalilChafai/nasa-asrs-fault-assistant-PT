# NASA ASRS Fault Assistant – Semantic Retrieval using SBERT

This project introduces a prototype AI fault assistant that leverages transformer models to retrieve semantically similar aviation incident reports from the NASA ASRS dataset using embedding on cleaned and processed narrative text. Using SBERT and computing similarity scores through cosine distance, the system enables engineers to quickly surface conceptually related incidents without relying on exact word overlap. A sample size of 1000 incidents was used from the ASRS aviation safety reports to demonstrate the working model. 

The project combines the implementation of NLP with practical safety analysis, aiming to reduce the turn around time from incident report to closure, as engineers can refer to previous methods used for similar incidents – guiding decision-making and reducing the time needed in training for companies forecasting lower training costs overall.

## Features

- Embeds narrative text using `all-MiniLM-L6-v2` SBERT model  
- Uses cosine similarity to retrive top-n most similar reports  
- Visualises embedding space using t-SNE  
- Highlights failure modes and outliers  
- Full analysis of similarity matches  
- Designed with future practical use cases in mind  

## What’s in the notebook?

-  Data loading and pre-proccessing  
-  SBERT embedding generation  
-  Cosine similarity ranking  
-  t-SNE clustering and interpetation  
-  Failure case analysis  
-  Extensive markdown walkthrough  
-  Full future work section  

## Dataset

- NASA ASRS Aviation Safety Reporting System dataset (uploaded via Kaggle)

##  References (Harvard Style)

- Mikolov, T., Chen, K., Corrado, G. and Dean, J., 2013. *Efficient estimation of word representations in vector space*. arXiv preprint arXiv:1301.3781.  
- Reimers, N. and Gurevych, I., 2019. *Sentence-BERT: Sentence embeddings using Siamese BERT-networks*. arXiv preprint arXiv:1908.10084.  
- Reimers, N. and Gurevych, I., 2020. *Making monolingual sentence embeddings multilingual using knowledge distillation*. arXiv preprint arXiv:2004.09813. 

---

> first-year computer science at Lancaster University  
> This assistant was designed as an early-stage prototype to demonstrate potential in incident retrieval and pattern matching.
