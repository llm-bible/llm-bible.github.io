---
layout: publication
title: 'Coascore: Chain-of-aspects Prompting For NLG Evaluation'
authors: Gong Peiyuan, Mao Jiaxin
conference: "Arxiv"
year: 2023
bibkey: gong2023chain
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.10355"}
tags: ['Applications', 'Prompting', 'RAG', 'Tools']
---
Recently, natural language generation (NLG) evaluation has shifted from a single-aspect to a multi-aspect paradigm, allowing for a more accurate assessment. Large language models (LLMs) achieve superior performance on various NLG evaluation tasks. However, current work often employs the LLM to independently evaluate different aspects, which largely ignores the rich correlation between various aspects. To fill this research gap, in this work, we propose an NLG evaluation metric called CoAScore. Powered by LLMs, the CoAScore utilizes multi-aspect knowledge through a CoA (\textbf\{C\}hain-\textbf\{o\}f-\textbf\{A\}spects) prompting framework when assessing the quality of a certain aspect. Specifically, for a given aspect to evaluate, we first prompt the LLM to generate a chain of aspects that are relevant to the target aspect and could be useful for the evaluation. We then collect evaluation scores for each generated aspect, and finally, leverage the knowledge of these aspects to improve the evaluation of the target aspect. We evaluate CoAScore across five NLG evaluation tasks (e.g., summarization, dialog response generation, etc) and nine aspects (e.g., overall quality, relevance, coherence, etc). Our experimental findings highlight that, in comparison to individual aspect evaluation, CoAScore exhibits a higher correlation with human judgments. This improvement significantly outperforms existing unsupervised evaluation metrics, whether for assessing overall quality or other aspects. We also conducted extensive ablation studies to validate the effectiveness of the three stages within the CoAScore framework and conducted case studies to show how the LLM performs in these stages. Our code and scripts are available.
