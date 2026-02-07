# Multi-Language Hate Speech Detection

## Overview
This project focuses on building a multi-language hate speech detection system designed to identify and classify hate speech on online content across two South-Asian languages, currently including Bengali and Nepali. With the rapid growth of social media communication in diverse linguistic communities, automated moderation tools often underperform for low-resource languages. This project aims to address that identified gap by developing a machine learning model and a deep learning model trained on expanded and carefully labeled multilingual datasets.

The system leverages an extended Bengali hate speech dataset alongside Nepali hate speech dataset that are further combined to support both binary hate speech detection (hate vs. non-hate) and fine-grained multi-label classification such as insult, violence, sexual content, racism, and religious hate across both the languages. By doing this, the project explores cross-lingual learning, improved generalization, and scalable moderation solutions for multilingual digital environments.

The goal is to contribute to responsible AI, safer online communities, and improved NLP resources for underrepresented languages, while supporting research in multilingual natural language processing, bias mitigation, and automated content moderation.

---

## Dataset Description
This dataset is an **expanded version** of the original sumaiya-afroze/Multi-Label_Bangla_Hate_Speech_Data created by Sumaiya Afroze.

The original dataset provided a strong foundation for hate speech detection in the Bengali language. In this extended version, the dataset has been:  
- **Expanded in size** with ~5000 additional Bengali social media comments.  
- **Reclassified with fine-grained categories**, including: *Insult, Violence, Sexual, Racism, Religious, and No Hate*.  

This makes the dataset suitable for **multi-label hate speech detection research**.  

 Data Modifications in This Version
- Expanded dataset size with additional Bengali text samples (~5000).  
- Introduced **multi-label classification categories**:  
- Hate/No Hate (binary indicator)  
  - If “Hate,” further classified into:  
    - Insult  
    - Violence  
    - Sexual  
    - Racism  
    - Religious  

---
## Model Evaluation

### Machine Learning Model


### Deep Learning Model

---
## Findings

---

## Acknowledgements  

This project was completed as part of the **CIS 631 – Machine Learning** course at **Minnesota State University, Mankato**. We sincerely thank **Dr. Mansi Bhavsar** for her guidance, valuable feedback, and continuous support throughout this project. Her mentorship and the academic environment fostered in the course encouraged exploration of socially impactful AI applications, particularly in the area of multilingual hate speech detection.  

This work builds upon previously developed datasets and research contributions from the NLP community. We would like to acknowledge the authors of one of the primary datasets used in this project:

### Bengali Hate Speech Dataset  

- **Authors:** Nauros Romim, Mosahed Ahmed, Hriteshwar Talukder, Md. Saiful Islam  
- **Dataset Name:** Bengali Hate Speech Dataset  
- **URL:** https://www.kaggle.com/datasets/naurosromim/bengali-hate-speech-dataset  
- **License:** CC BY-NC 4.0  
- **Paper:** https://arxiv.org/pdf/2012.09686  

### Nepali Hate Speech Dataset  



Their contributions have significantly supported research in hate speech detection for low-resource languages. Additional dataset acknowledgements will be added as the project expands.  

### Reference Research Paper  

- **Title:** Machine Learning- and Deep Learning-Based Multi-Model System for Hate Speech Detection on Facebook  
- **Authors:** Amna Naseeb, Muhammad Zain, Nisar Hussain, Amna Qasim, Fiaz Ahmad, Grigori Sidorov, Alexander Gelbukh  
- **Venue:** Algorithms (MDPI), Peer-Reviewed Journal, 2025  
- **DOI:** https://doi.org/10.3390/a18060331  

This research informed the methodological direction and comparative modeling approach used in this project.

---

*Busrat Jahan* || *Roshit Niraula*
