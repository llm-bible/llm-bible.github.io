---
layout: publication
title: Infobert Improving Robustness Of Language Models From An Information Theoretic Perspective
authors: Wang Boxin, Wang Shuohang, Cheng Yu, Gan Zhe, Jia Ruoxi, Li Bo, Liu Jingjing
conference: "Arxiv"
year: 2020
bibkey: wang2020improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2010.02329"}
  - {name: "Code", url: "https://github.com/AI&#45;secure/InfoBERT"}
tags: ['Applications', 'BERT', 'Has Code', 'Model Architecture', 'Security', 'Tools', 'Training Techniques']
---
Large45;scale language models such as BERT have achieved state45;of45;the45;art performance across a wide range of NLP tasks. Recent studies however show that such BERT45;based models are vulnerable facing the threats of textual adversarial attacks. We aim to address this problem from an information45;theoretic perspective and propose InfoBERT a novel learning framework for robust fine45;tuning of pre45;trained language models. InfoBERT contains two mutual45;information45;based regularizers for model training (i) an Information Bottleneck regularizer which suppresses noisy mutual information between the input and the feature representation; and (ii) a Robust Feature regularizer which increases the mutual information between local robust features and global features. We provide a principled way to theoretically analyze and improve the robustness of representation learning for language models in both standard and adversarial training. Extensive experiments demonstrate that InfoBERT achieves state45;of45;the45;art robust accuracy over several adversarial datasets on Natural Language Inference (NLI) and Question Answering (QA) tasks. Our code is available at https://github.com/AI&#45;secure/InfoBERT.
