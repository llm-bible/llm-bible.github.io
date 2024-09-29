---
layout: publication
title: Data Engineering For Scaling Language Models To 128K Context
authors: Fu Yao, Panda Rameswar, Niu Xinyao, Yue Xiang, Hajishirzi Hannaneh, Kim Yoon, Peng Hao
conference: "Arxiv"
year: 2024
bibkey: fu2024data
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.10171"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Training Techniques']
---
We study the continual pretraining recipe for scaling language models context lengths to 128K with a focus on data engineering. We hypothesize that long context modeling in particular textit123;the ability to utilize information at arbitrary input locations125; is a capability that is mostly already acquired through large45;scale pretraining and that this capability can be readily extended to contexts substantially longer than seen during training~(e.g. 4K to 128K) through lightweight continual pretraining on appropriate data mixture. We investigate the textit123;quantity125; and textit123;quality125; of the data for continual pretraining (1) for quantity we show that 500 million to 5 billion tokens are enough to enable the model to retrieve information anywhere within the 128K context; (2) for quality our results equally emphasize textit123;domain balance125; and textit123;length upsampling125;. Concretely we find that naively upsampling longer data on certain domains like books a common practice of existing work gives suboptimal performance and that a balanced domain mixture is important. We demonstrate that continual pretraining of the full model on 1B45;5B tokens of such data is an effective and affordable strategy for scaling the context length of language models to 128K. Our recipe outperforms strong open45;source long45;context models and closes the gap to frontier models like GPT45;4 128K.
