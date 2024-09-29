---
layout: publication
title: Data Contamination Can Cross Language Barriers
authors: Yao Feng, Zhuang Yufan, Sun Zihao, Xu Sunan, Kumar Animesh, Shang Jingbo
conference: "Arxiv"
year: 2024
bibkey: yao2024data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.13236"}
  - {name: "Code", url: "https://github.com/ShangDataLab/Deep-Contam"}
tags: ['Has Code', 'Pretraining Methods', 'Reinforcement Learning', 'Training Techniques']
---
The opacity in developing large language models (LLMs) is raising growing concerns about the potential contamination of public benchmarks in the pre-training data. Existing contamination detection methods are typically based on the text overlap between training and evaluation data which can be too superficial to reflect deeper forms of contamination. In this paper we first present a cross-lingual form of contamination that inflates LLMs performance while evading current detection methods deliberately injected by overfitting LLMs on the translated versions of benchmark test sets. Then we propose generalization-based approaches to unmask such deeply concealed contamination. Specifically we examine the LLMs performance change after modifying the original benchmark by replacing the false answer choices with correct ones from other questions. Contaminated models can hardly generalize to such easier situations where the false choices can be (emph)not even wrong as all choices are correct in their memorization. Experimental results demonstrate that cross-lingual contamination can easily fool existing detection methods but not ours. In addition we discuss the potential utilization of cross-lingual contamination in interpreting LLMs working mechanisms and in post-training LLMs for enhanced multilingual capabilities. The code and dataset we use can be obtained from (url)https://github.com/ShangDataLab/Deep-Contam\}.
