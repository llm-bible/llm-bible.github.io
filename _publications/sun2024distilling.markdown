---
layout: publication
title: 'Delrec: Distilling Sequential Pattern To Enhance Llm-based Recommendation'
authors: Sun Guohao, Zhang Haoyi
conference: "Arxiv"
year: 2024
bibkey: sun2024distilling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11156"}
tags: ['Interpretability And Explainability', 'Prompting', 'Tools', 'Training Techniques']
---
Sequential recommendation (SR) tasks enhance recommendation accuracy by
capturing the connection between users' past interactions and their changing
preferences. Conventional models often focus solely on capturing sequential
patterns within the training data, neglecting the broader context and semantic
information embedded in item titles from external sources. This limits their
predictive power and adaptability. Recently, large language models (LLMs) have
shown promise in SR tasks due to their advanced understanding capabilities and
strong generalization abilities. Researchers have attempted to enhance LLMs'
recommendation performance by incorporating information from SR models.
However, previous approaches have encountered problems such as 1) only
influencing LLMs at the result level; 2) increased complexity of LLMs
recommendation methods leading to reduced interpretability; 3) incomplete
understanding and utilization of SR models information by LLMs.
  To address these problems, we proposes a novel framework, DELRec, which aims
to extract knowledge from SR models and enable LLMs to easily comprehend and
utilize this supplementary information for more effective sequential
recommendations. DELRec consists of two main stages: 1) SR Models Pattern
Distilling, focusing on extracting behavioral patterns exhibited by SR models
using soft prompts through two well-designed strategies; 2) LLMs-based
Sequential Recommendation, aiming to fine-tune LLMs to effectively use the
distilled auxiliary information to perform SR tasks. Extensive experimental
results conducted on three real datasets validate the effectiveness of the
DELRec framework.
