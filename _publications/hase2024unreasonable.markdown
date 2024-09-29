---
layout: publication
title: The Unreasonable Effectiveness Of Easy Training Data For Hard Tasks
authors: Hase Peter, Bansal Mohit, Clark Peter, Wiegreffe Sarah
conference: "Arxiv"
year: 2024
bibkey: hase2024unreasonable
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06751"}
  - {name: "Code", url: "https://github.com/allenai/easy&#45;to&#45;hard&#45;generalization"}
tags: ['Attention Mechanism', 'Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
How can we train models to perform well on hard test data when hard training data is by definition difficult to label correctly This question has been termed the scalable oversight problem and has drawn increasing attention as language models have continually improved. In this paper we present the surprising conclusion that current pretrained language models often generalize relatively well from easy to hard data even performing as well as oracle models finetuned on hard data. We demonstrate this kind of easy45;to45;hard generalization using simple finetuning methods like in45;context learning linear classifier heads and QLoRA for seven different measures of datapoint hardness including six empirically diverse human hardness measures (like grade level) and one model45;based measure (loss45;based). Furthermore we show that even if one cares most about model performance on hard data it can be better to collect easy data rather than hard data for finetuning since hard data is generally noisier and costlier to collect. Our experiments use open models up to 70b in size and four publicly available question45;answering datasets with questions ranging in difficulty from 3rd grade science questions to college level STEM questions and general45;knowledge trivia. We conclude that easy45;to45;hard generalization in LMs is surprisingly strong for the tasks studied. Our code is available at https://github.com/allenai/easy&#45;to&#45;hard&#45;generalization
