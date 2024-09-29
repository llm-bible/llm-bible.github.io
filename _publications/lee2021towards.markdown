---
layout: publication
title: "Towards Few-shot Fact-checking Via Perplexity"
authors: Lee Nayeon, Bang Yejin, Madotto Andrea, Khabsa Madian, Fung Pascale
conference: "Arxiv"
year: 2021
bibkey: lee2021towards
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2103.09535"}
tags: ['Applications', 'Attention Mechanism', 'Few Shot', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
Few-shot learning has drawn researchers attention to overcome the problem of data scarcity. Recently large pre-trained language models have shown great performance in few-shot learning for various downstream tasks such as question answering and machine translation. Nevertheless little exploration has been made to achieve few-shot learning for the fact-checking task. However fact-checking is an important problem especially when the amount of information online is growing exponentially every day. In this paper we propose a new way of utilizing the powerful transfer learning ability of a language model via a perplexity score. The most notable strength of our methodology lies in its capability in few-shot learning. With only two training samples our methodology can already outperform the Major Class baseline by more than absolute 1037; on the F1-Macro metric across multiple datasets. Through experiments we empirically verify the plausibility of the rather surprising usage of the perplexity score in the context of fact-checking and highlight the strength of our few-shot methodology by comparing it to strong fine-tuning-based baseline models. Moreover we construct and publicly release two new fact-checking datasets related to COVID-19.
