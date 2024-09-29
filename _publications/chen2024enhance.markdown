---
layout: publication
title: 'Elcorec: Enhance Language Understanding With Co-propagation Of Numerical And Categorical Features For Recommendation'
authors: Chen Jizheng, Du Kounianhua, Lin Jianghao, Chen Bo, Tang Ruiming, Zhang Weinan
conference: "Arxiv"
year: 2024
bibkey: chen2024enhance
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.18825"}
  - {name: "Code", url: "https://anonymous.4open.science/r/CIKM_Code_Repo-E6F5/README.md"}
tags: ['Attention Mechanism', 'Has Code', 'Model Architecture', 'Multimodal Models', 'Prompting']
---
Large language models have been flourishing in the natural language processing (NLP) domain and their potential for recommendation has been paid much attention to. Despite the intelligence shown by the recommendation-oriented finetuned models LLMs struggle to fully understand the user behavior patterns due to their innate weakness in interpreting numerical features and the overhead for long context where the temporal relations among user behaviors subtle quantitative signals among different ratings and various side features of items are not well explored. Existing works only fine-tune a sole LLM on given text data without introducing that important information to it leaving these problems unsolved. In this paper we propose ELCoRec to Enhance Language understanding with CoPropagation of numerical and categorical features for Recommendation. Concretely we propose to inject the preference understanding capability into LLM via a GAT expert model where the user preference is better encoded by parallelly propagating the temporal relations and rating signals as well as various side information of historical items. The parallel propagation mechanism could stabilize heterogeneous features and offer an informative user preference encoding which is then injected into the language models via soft prompting at the cost of a single token embedding. To further obtain the users recent interests we proposed a novel Recent interaction Augmented Prompt (RAP) template. Experiment results over three datasets against strong baselines validate the effectiveness of ELCoRec. The code is available at https://anonymous.4open.science/r/CIKM\_Code\_Repo-E6F5/README.md."
