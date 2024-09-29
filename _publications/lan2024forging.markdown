---
layout: publication
title: 'FOCUS: Forging Originality Through Contrastive Use In Self-plagiarism For Language Models'
authors: Lan Kaixin, Fang Tao, Wong Derek F., Xu Yabo, Chao Lidia S., Zhao Cecilia G.
conference: "Arxiv"
year: 2024
bibkey: lan2024forging
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.00839"}
tags: ['Applications', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
Pre-trained Language Models (PLMs) have shown impressive results in various Natural Language Generation (NLG) tasks such as powering chatbots and generating stories. However an ethical concern arises due to their potential to produce verbatim copies of paragraphs from their training data. This is problematic as PLMs are trained on corpora constructed by human authors. As such there is a pressing need for research to promote the generation of original content by these models. In this study we introduce a unique self-plagiarism contrastive decoding strategy aimed at boosting the originality of text produced by PLMs. Our method entails modifying prompts in LLMs to develop an amateur model and a professional model. Specifically the amateur model is urged to plagiarize using three plagiarism templates we have designed while the professional model maintains its standard language model status. This strategy employs prompts to stimulate the models capacity to identify non-original candidate token combinations and subsequently impose penalties. The application of this strategy is integrated prior to the models final layer ensuring smooth integration with most existing PLMs (T5 GPT LLaMA) without necessitating further adjustments. Implementing our strategy we observe a significant decline in non-original sequences comprised of more than three words in the academic AASC dataset and the story-based ROCStories dataset.
