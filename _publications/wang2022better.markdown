---
layout: publication
title: Qrelscore&#58; Better Evaluating Generated Questions With Deeper Understanding Of Context-aware Relevance
authors: Wang Xiaoqiang, Liu Bang, Tang Siliang, Wu Lingfei
conference: "Arxiv"
year: 2022
bibkey: wang2022better
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2204.13921"}
tags: ['BERT', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Security']
---
Existing metrics for assessing question generation not only require costly human reference but also fail to take into account the input context of generation rendering the lack of deep understanding of the relevance between the generated questions and input contexts. As a result they may wrongly penalize a legitimate and reasonable candidate question when it (i) involves complicated reasoning with the context or (ii) can be grounded by multiple evidences in the context. In this paper we propose (textbfQRelScore) a context-aware (underline)(textbfRel)evance evaluation metric for (underline)(textbfQ)uestion Generation. Based on off-the-shelf language models such as BERT and GPT2 QRelScore employs both word-level hierarchical matching and sentence-level prompt-based generation to cope with the complicated reasoning and diverse generation from multiple evidences respectively. Compared with existing metrics our experiments demonstrate that QRelScore is able to achieve a higher correlation with human judgments while being much more robust to adversarial samples.
