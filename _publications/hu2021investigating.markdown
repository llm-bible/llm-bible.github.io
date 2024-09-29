---
layout: publication
title: Investigating Transfer Learning in Multilingual Pre-trained Language Models through Chinese Natural Language Inference
authors: Hu Hai, Zhou He, Tian Zuoyu, Zhang Yiwen, Ma Yina, Li Yanting, Nie Yixin, Richardson Kyle
conference: "Arxiv"
year: 2021
bibkey: hu2021investigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2106.03983"}
  - {name: "Code", url: "https://github.com/huhailinguist/ChineseNLIProbing"}
tags: ['Fine Tuning', 'Has Code', 'Model Architecture', 'Pretraining Methods', 'Security', 'Transformer']
---
Multilingual transformers (XLM mT5) have been shown to have remarkable transfer skills in zero-shot settings. Most transfer studies however rely on automatically translated resources (XNLI XQuAD) making it hard to discern the particular linguistic knowledge that is being transferred and the role of expert annotated monolingual datasets when developing task-specific models. We investigate the cross-lingual transfer abilities of XLM-R for Chinese and English natural language inference (NLI) with a focus on the recent large-scale Chinese dataset OCNLI. To better understand linguistic transfer we created 4 categories of challenge and adversarial tasks (totaling 17 new datasets) for Chinese that build on several well-known resources for English (e.g. HANS NLI stress-tests). We find that cross-lingual models trained on English NLI do transfer well across our Chinese tasks (e.g. in 3/4 of our challenge categories they perform as well/better than the best monolingual models even on 3/5 uniquely Chinese linguistic phenomena such as idioms pro drop). These results however come with important caveats cross-lingual models often perform best when trained on a mixture of English and high-quality monolingual NLI data (OCNLI) and are often hindered by automatically translated resources (XNLI-zh). For many phenomena all models continue to struggle highlighting the need for our new diagnostics to help benchmark Chinese and cross-lingual models. All new datasets/code are released at https://github.com/huhailinguist/ChineseNLIProbing.
