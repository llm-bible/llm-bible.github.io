---
layout: publication
title: Language Models As Knowledge Bases
authors: Petroni Fabio, Rocktäschel Tim, Lewis Patrick, Bakhtin Anton, Wu Yuxiang, Miller Alexander H., Riedel Sebastian
conference: "Arxiv"
year: 2019
bibkey: petroni2019language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/1909.01066"}
  - {name: "Code", url: "https://github.com/facebookresearch/LAMA"}
tags: ['Applications', 'BERT', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Recent progress in pretraining language models on large textual corpora led to a surge of improvements for downstream NLP tasks. Whilst learning linguistic knowledge these models may also be storing relational knowledge present in the training data and may be able to answer queries structured as fill45;in45;the45;blank cloze statements. Language models have many advantages over structured knowledge bases they require no schema engineering allow practitioners to query about an open class of relations are easy to extend to more data and require no human supervision to train. We present an in45;depth analysis of the relational knowledge already present (without fine45;tuning) in a wide range of state45;of45;the45;art pretrained language models. We find that (i) without fine45;tuning BERT contains relational knowledge competitive with traditional NLP methods that have some access to oracle knowledge (ii) BERT also does remarkably well on open45;domain question answering against a supervised baseline and (iii) certain types of factual knowledge are learned much more readily than others by standard language model pretraining approaches. The surprisingly strong ability of these models to recall factual knowledge without any fine45;tuning demonstrates their potential as unsupervised open45;domain QA systems. The code to reproduce our analysis is available at https://github.com/facebookresearch/LAMA.
