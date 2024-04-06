# [EACL-2024](https://2024.eacl.org/)

<img title="" src="Figures\EACL.jpeg" alt="">

Code and dataset of the tasks are released here. In order to use the dataset interested ones have to follow policy of workshop organizers.

# Shared Task#5 (HOLD-Telugu)

## Hate and Offensive Language Detection in Telugu Codemixed Text

**Author:** Nafisa Tabassum, Mosabbir Hossain Khan, Shawly Ahsan, Jawad Hossain, and Mohammed Moshiul Hoque

**Venue:** Shared task description paper of DravidianLangTech workshop collocated with EACL-2024. [DravidianLangTech@EACL2024](https://sites.google.com/view/dravidianlangtech-2024/home)

**Paper Link:** [https://aclanthology.org/2024.dravidianlangtech-1.28/](https://aclanthology.org/2024.dravidianlangtech-1.28/)

## Abstract

Hate and offensive language in online platforms pose significant challenges, necessitating automatic detection methods. Particularly in the case of codemixed text, which is very common in social media, the complexity of this problem increases due to the cultural nuances of different languages. DravidianLangTech-EACL2024 organized a shared task on detecting hate and offensive language for Telugu. To complete this task, this study investigates the effectiveness of transliteration-augmented datasets for Telugu code-mixed text. In this work, we compare the performance of various machine learning (ML), deep learning (DL), and transformer-based models on both original and augmented datasets. Experimental findings demonstrate the superiority of transformer models, particularly Telugu-BERT, achieving the highest $f_1$-score of 0.77 on the augmented dataset, **ranking the $1^{st}$ position** in the leaderboard. The study highlights the potential of transliteration-augmented datasets in improving model performance and suggests further exploration of diverse transliteration options to address real-world scenarios.

## Contribution

- Developed a transliteration-based augmentation scheme to help transformer models detect code-mixed Telugu offensive texts with high fidelity.
- Investigated various Ml, DL, and transformer-based techniques for the task and analyzed their performance in augmented and non-augmented datasets.

## Dataset Analysis

The number of instances used to train, validate and test the models summarized in Table 1.

<img title="" src="Figures\Data_Stat.PNG" alt="">

## System Overview

Figure 1 represents the transliteration-augmentation process.

<p align = "center">
<img title="" src="Figures\Transliteration_process.PNG" alt="">
</p>

Figure 2 presents the schematic diagram of our system, which has three major phases: preprocessing, feature extraction and classification.

<p align = "center">
<img title="" src="Figures\Methodology.PNG" alt="">
</p>

## Results

Table 2 presents the evaluation results of the tasks on the test set.

<img title="" src="Figures\Result.PNG" alt="">

Figure 3 presents the confusion matrices of the best model for each language.

<img title="" src="Figures\confusion_matrix.png" alt="">

## Conclusion

This paper explored various ML, DL, and transformer-based approaches for hate and offensive language detection in Telugu code-mixed text and demonstrated the effectiveness of transliteration-augmented datasets. In most cases, transformer models outperformed ML and DL methods. Telugu-BERT, trained explicitly on Telugu text, achieved an impressive $f_1$ score of 0.77. Investigating further augmentation methods and their combinations presents an exciting future direction to enhance the dataset and improve performance.



## Ackonwlegement
All the works are supported and funded by [CUET NLP Lab](https://cuetnlp.com/). Besides, we are thanking to [Prof. Dr. Mohammed Moshiul Hoque](https://www.researchgate.net/profile/Moshiul_Hoque) for his valuable guidance.

## Citation
If you use our work please consider citing our paper:
```
@inproceedings{tabassum2024sandalphon,
  title={Sandalphon@ DravidianLangTech-EACL2024: Hate and Offensive Language Detection in Telugu Code-mixed Text using Transliteration-Augmentation},
  author={Tabassum, Nafisa and Khan, Mosabbir and Ahsan, Shawly and Hossain, Jawad and Hoque, Mohammed Moshiul},
  booktitle={Proceedings of the Fourth Workshop on Speech, Vision, and Language Technologies for Dravidian Languages},
  pages={167--172},
  year={2024}
}
```

