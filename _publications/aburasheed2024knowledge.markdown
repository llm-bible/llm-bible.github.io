---
layout: publication
title: Knowledge Graphs as Context Sources for LLM-Based Explanations of Learning Recommendations
authors: Abu-rasheed Hasan, Weber Christian, Fathi Madjid
conference: "Arxiv"
year: 2024
bibkey: aburasheed2024knowledge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.03008"}
tags: ['Applications', 'GPT', 'Interpretability And Explainability', 'Model Architecture', 'Prompting']
---
In the era of personalized education the provision of comprehensible explanations for learning recommendations is of a great value to enhance the learners understanding and engagement with the recommended learning content. Large language models (LLMs) and generative AI in general have recently opened new doors for generating human-like explanations for and along learning recommendations. However their precision is still far away from acceptable in a sensitive field like education. To harness the abilities of LLMs while still ensuring a high level of precision towards the intent of the learners this paper proposes an approach to utilize knowledge graphs (KG) as a source of factual context for LLM prompts reducing the risk of model hallucinations and safeguarding against wrong or imprecise information while maintaining an application-intended learning context. We utilize the semantic relations in the knowledge graph to offer curated knowledge about learning recommendations. With domain-experts in the loop we design the explanation as a textual template which is filled and completed by the LLM. Domain experts were integrated in the prompt engineering phase as part of a study to ensure that explanations include information that is relevant to the learner. We evaluate our approach quantitatively using Rouge-N and Rouge-L measures as well as qualitatively with experts and learners. Our results show an enhanced recall and precision of the generated explanations compared to those generated solely by the GPT model with a greatly reduced risk of generating imprecise information in the final learning explanation.
