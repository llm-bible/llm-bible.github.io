---
layout: publication
title: 'Preference Discerning With Llm-enhanced Generative Retrieval'
authors: Fabian Paischer, Liu Yang, Linfeng Liu, Shuai Shao, Kaveh Hassani, Jiacheng Li, Ricky Chen, Zhang Gabriel Li, Xialo Gao, Wei Shao, Xue Feng, Nima Noorshams, Sem Park, Bo Long, Hamid Eghbalzadeh
conference: "Arxiv"
year: 2024
bibkey: paischer2024preference
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.08604'}
tags: ['Training Techniques']
---
Sequential recommendation systems aim to provide personalized recommendations
for users based on their interaction history. To achieve this, they often
incorporate auxiliary information, such as textual descriptions of items and
auxiliary tasks, like predicting user preferences and intent. Despite numerous
efforts to enhance these models, they still suffer from limited
personalization. To address this issue, we propose a new paradigm, which we
term preference discerning. In preference dscerning, we explicitly condition a
generative sequential recommendation system on user preferences within its
context. To this end, we generate user preferences using Large Language Models
(LLMs) based on user reviews and item-specific data. To evaluate preference
discerning capabilities of sequential recommendation systems, we introduce a
novel benchmark that provides a holistic evaluation across various scenarios,
including preference steering and sentiment following. We assess current
state-of-the-art methods using our benchmark and show that they struggle to
accurately discern user preferences. Therefore, we propose a new method named
Mender (\\(\textbf\{M\}\\)ultimodal Prefer\\(\textbf\{en\}\\)ce
\\(\textbf\{d\}\\)iscern\\(\textbf\{er\}\\)), which improves upon existing methods and
achieves state-of-the-art performance on our benchmark. Our results show that
Mender can be effectively guided by human preferences even though they have not
been observed during training, paving the way toward more personalized
sequential recommendation systems. We will open-source the code and benchmarks
upon publication.
