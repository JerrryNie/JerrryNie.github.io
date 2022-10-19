---
title: "Unsupervised Question Answering via Answer Diversifying"
collection: publications
permalink: /publication/2022-08-15-unsupervised-question-answering-via-answer-diversifying
excerpt: 'In this study, we propose a method, called **DiverseQA**, to tackle the problem of diversifying answers in unsupervised question answering. Specifically, **DiverseQA** is composed of three modules: data construction, data augmentation and denoising filter. Firstly, the data construction module extends the extracted named entity into a longer sentence constituent as the new answer span to construct a QA dataset with diverse answers. Secondly, the data augmentation module adopts an answer-type dependent data augmentation process via adversarial training in the embedding level. Thirdly, the denoising filter module is designed to alleviate the noise in the constructed data. Extensive experiments show that **DiverseQA** outperforms pervious unsupervised methods on five benchmark datasets, including SQuADv1.1, NewsQA, TriviaQA, BioASQ, and DuoRC. Besides, it shows strong performance in the few-shot learning.'
date: 2022-08-15
venue: 'COLING 2022'
paperurl: 'https://aclanthology.org/2022.coling-1.149/'
citation: 'Yuxiang Nie, Heyan Huang, Zewen Chi, and Xian-Ling Mao. 2022. Unsupervised Question Answering via Answer Diversifying. In Proceedings of the 29th International Conference on Computational Linguistics, pages 1732–1742, Gyeongju, Republic of Korea. International Committee on Computational Linguistics.'
---

## Abstract
Unsupervised question answering is an attractive task due to its independence on labeled data. Previous works usually make use of heuristic rules as well as pre-trained models to construct data and train QA models. However, most of these works regard named entity (NE) as the only answer type, which ignores the high diversity of answers in the real world. To tackle this problem, we propose a novel unsupervised method by diversifying answers, named DiverseQA. Specifically, the proposed method is composed of three modules: data construction, data augmentation and denoising filter. Firstly, the data construction module extends the extracted named entity into a longer sentence constituent as the new answer span to construct a QA dataset with diverse answers. Secondly, the data augmentation module adopts an answer-type dependent data augmentation process via adversarial training in the embedding level. Thirdly, the denoising filter module is designed to alleviate the noise in the constructed data. Extensive experiments show that the proposed method outperforms previous unsupervised models on five benchmark datasets, including SQuADv1.1, NewsQA, TriviaQA, BioASQ, and DuoRC. Besides, the proposed method shows strong performance in the few-shot learning setting.

[Download paper here](https://aclanthology.org/2022.coling-1.149.pdf)

Recommended citation: Yuxiang Nie, Heyan Huang, Zewen Chi, and Xian-Ling Mao. 2022. Unsupervised Question Answering via Answer Diversifying. In Proceedings of the 29th International Conference on Computational Linguistics, pages 1732–1742, Gyeongju, Republic of Korea. International Committee on Computational Linguistics.
