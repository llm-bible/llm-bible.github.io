---
layout: publication
title: 'Mascqa: A Question Answering Dataset For Investigating Materials Science Knowledge Of Large Language Models'
authors: Mohd Zaki, Jayadeva, Mausam, N. M. Anoop Krishnan
conference: "Arxiv"
year: 2023
bibkey: zaki2023question
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.09115"}
tags: ['Prompting', 'Model Architecture', 'Applications', 'GPT']
---
Information extraction and textual comprehension from materials literature
are vital for developing an exhaustive knowledge base that enables accelerated
materials discovery. Language models have demonstrated their capability to
answer domain-specific questions and retrieve information from knowledge bases.
However, there are no benchmark datasets in the materials domain that can
evaluate the understanding of the key concepts by these language models. In
this work, we curate a dataset of 650 challenging questions from the materials
domain that require the knowledge and skills of a materials student who has
cleared their undergraduate degree. We classify these questions based on their
structure and the materials science domain-based subcategories. Further, we
evaluate the performance of GPT-3.5 and GPT-4 models on solving these questions
via zero-shot and chain of thought prompting. It is observed that GPT-4 gives
the best performance (~62% accuracy) as compared to GPT-3.5. Interestingly, in
contrast to the general observation, no significant improvement in accuracy is
observed with the chain of thought prompting. To evaluate the limitations, we
performed an error analysis, which revealed conceptual errors (~64%) as the
major contributor compared to computational errors (~36%) towards the reduced
performance of LLMs. We hope that the dataset and analysis performed in this
work will promote further research in developing better materials science
domain-specific LLMs and strategies for information extraction.
