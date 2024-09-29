---
layout: publication
title: Self45;prompting Large Language Models For Zero45;shot Open45;domain QA
authors: Junlong Li, Jinyuan Wang, Zhuosheng Zhang, Hai Zhao
conference: "Arxiv"
year: 2022
bibkey: li2022self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2212.08635v3"}
  - {name: "Code", url: "https://github.com/lockon&#45;n/self&#45;prompting"}
tags: ['Applications', 'GPT', 'Has Code', 'Interpretability And Explainability', 'Model Architecture', 'Prompting', 'Tools', 'Training Techniques']
---
Open45;Domain Question Answering (ODQA) aims to answer questions without explicitly providing specific background documents. This task becomes notably challenging in a zero45;shot setting where no data is available to train tailored retrieval45;reader models. While recent Large Language Models (LLMs) like GPT45;3 have demonstrated their effectiveness in zero45;shot ODQA using direct prompting methods these methods still fall short of fully harnessing the potential of LLMs when implicitly invoked. In this paper we propose a Self45;Prompting framework to explicitly utilize the massive knowledge encoded in the parameters of LLMs and their strong instruction understanding abilities. Concretely we prompt LLMs step by step to generate multiple pseudo QA pairs with background passages and explanations entirely from scratch. These generated elements are then utilized for in45;context learning. Experimental results show that our method significantly surpasses previous state45;of45;the45;art zero45;shot methods on three widely45;used ODQA datasets and even achieves comparable performance with various customized fine45;tuned models on full training data. Our code is available at https://github.com/lockon&#45;n/self&#45;prompting.
