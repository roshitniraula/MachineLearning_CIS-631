---
license: cc-by-nc-4.0
task_categories:
- text-classification
language:
- bn
tags:
- Bengali
- Bangla
- HateSpeech
- HateData
- Hate
- Multilabel
- Multi-label
pretty_name: Multi-label Bangla Hate Speech Data
size_categories:
- 10K<n<100K
---




readme_text = """
# Bangla Hate Speech Extended Dataset

## Overview of DataSets
This dataset is an **expanded version** of the original [Bengali Hate Speech Dataset](https://www.kaggle.com/datasets/naurosromim/bengali-hate-speech-dataset) created by **Hriteshwar Talukder** and **Md Saiful Islam**.  

The original dataset provided a strong foundation for hate speech detection in the Bengali language. In this extended version, the dataset has been:  
- **Expanded in size** with ~5000 additional Bengali social media comments.  
- **Reclassified with fine-grained categories**, including: *Insult, Violence, Sexual, Racism, Religious, and No Hate*.  

This makes the dataset suitable for **multi-label hate speech detection research**.  

---

## 📂 Source Dataset
- **Name:** Bengali Hate Speech Dataset  
- **Authors:** Hriteshwar Talukder, Md Saiful Islam  
- **URL:** [Kaggle Link](https://www.kaggle.com/datasets/naurosromim/bengali-hate-speech-dataset)  
- **Paper:** [Official Publication](https://arxiv.org/pdf/2012.09686)  
- **License:** [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)  
- **Citation:** Romim, N., Ahmed, M., Talukder, H., & Islam, M. S. (2020). Hate Speech detection in the Bengali language: A dataset and its baseline evaluation. arXiv preprint arXiv:2012.09686. 



---

## 🔧 Modifications in This Version
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

## 📜 License
This dataset is released under the **[Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)** license, in line with the original dataset.  

You are free to use, share, and adapt this dataset for **non-commercial research and educational purposes**, provided that appropriate credit is given to both the **original authors** and the **expanded dataset creator**.  

---

## 🙏 Acknowledgements
This work builds upon the original dataset created by **Nauros Romim**, **Mosahed Ahmed**, **Hriteshwar Talukder** and **Md Saiful Islam**. Special thanks to the authors for their valuable contribution to Bengali NLP research.  


