---
layout: publication
title: Improving Language Models Via Plug45;and45;play Retrieval Feedback
authors: Yu Wenhao, Zhang Zhihan, Liang Zhenwen, Jiang Meng, Sabharwal Ashish
conference: "Arxiv"
year: 2023
bibkey: yu2023improving
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14002"}
tags: ['Applications', 'Pretraining Methods', 'Reinforcement Learning', 'Tools']
---
Large language models (LLMs) exhibit remarkable performance across various NLP tasks. However they often generate incorrect or hallucinated information which hinders their practical applicability in real45;world scenarios. Human feedback has been shown to effectively enhance the factuality and quality of generated content addressing some of these limitations. However this approach is resource45;intensive involving manual input and supervision which can be time45;consuming and expensive. Moreover it cannot be provided during inference further limiting its practical utility in dynamic and interactive applications. In this paper we introduce ReFeed a novel pipeline designed to enhance LLMs by providing automatic retrieval feedback in a plug45;and45;play framework without the need for expensive fine45;tuning. ReFeed first generates initial outputs then utilizes a retrieval model to acquire relevant information from large document collections and finally incorporates the retrieved information into the in45;context demonstration for output refinement thereby addressing the limitations of LLMs in a more efficient and cost45;effective manner. Experiments on four knowledge45;intensive benchmark datasets demonstrate our proposed ReFeed could improve over +6.037; under zero45;shot setting and +2.537; under few45;shot setting compared to baselines without using retrieval feedback.
