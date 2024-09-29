---
layout: publication
title: Reformulating Domain Adaptation Of Large Language Models As Adapt45;retrieve45;revise A Case Study On Chinese Legal Domain
authors: Wan Zhen, Zhang Yating, Wang Yexiang, Cheng Fei, Kurohashi Sadao
conference: "Arxiv"
year: 2023
bibkey: wan2023reformulating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03328"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'GPT', 'Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools', 'Training Techniques']
---
While large language models (LLMs) like GPT45;4 have recently demonstrated astonishing zero45;shot capabilities in general domain tasks they often generate content with hallucinations in specific domains such as Chinese law hindering their application in these areas. This is typically due to the absence of training data that encompasses such a specific domain preventing GPT45;4 from acquiring in45;domain knowledge. A pressing challenge is that its not plausible to continue training LLMs of such scale on in45;domain data. This paper introduces a simple and effective domain adaptation framework for GPT45;4 by reformulating generation as an textbf123;adapt45;retrieve45;revise125; process. The initial step is to textbf123;adapt125; an affordable 7B LLM to the target domain by continuing learning on in45;domain data. When solving a task we leverage the adapted LLM to generate a draft answer given a task query. Then the draft answer will be used to textbf123;retrieve125; supporting evidence candidates from an external in45;domain knowledge base. Finally the draft answer and retrieved evidence are concatenated into a whole prompt to let GPT45;4 assess the evidence and textbf123;revise125; the draft answer to generate the final answer. Our proposal combines the advantages of the efficiency of adapting a smaller 7B model with the evidence45;assessing capability of GPT45;4 and effectively prevents GPT45;4 from generating hallucinatory content. In the zero45;shot setting of four Chinese legal tasks our method improves accuracy by 33.337; compared to the direct generation by GPT45;4. When compared to two stronger retrieval45;based baselines our method outperforms them by 15.437; and 23.937;. Our code will be released
