---
layout: publication
title: Leveraging Web45;crawled Data For High45;quality Fine45;tuning
authors: Zhou Jing, Jiang Chenglin, Shen Wei, Zhou Xiao, He Xiaonan
conference: "Arxiv"
year: 2024
bibkey: zhou2024leveraging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08003"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Training Techniques']
---
Most large language models are fine45;tuned using either expensive human45;annotated data or GPT45;4 generated data which cannot guarantee performance in certain domains. We argue that although the web45;crawled data often has formatting errors causing semantic inaccuracies it can still serve as a valuable source for high45;quality supervised fine45;tuning in specific domains without relying on advanced models like GPT45;4. To this end we create a paired training dataset automatically by aligning web45;crawled data with a smaller set of high45;quality data. By training a language model on this dataset we can convert web data with irregular formats into high45;quality ones. Our experiments show that training with the model45;transformed data yields better results surpassing training with only high45;quality data by an average score of 9.437; in Chinese math problems. Additionally our 7B model outperforms several open45;source models larger than 32B and surpasses well45;known closed45;source models such as GPT45;3.5 highlighting the efficacy of our approach.
