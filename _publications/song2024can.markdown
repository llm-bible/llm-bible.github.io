---
layout: publication
title: Can Many-shot In-context Learning Help Long-context LLM Judges? See More, Judge Better!
authors: Song Mingyang, Zheng Mao, Luo Xuan
conference: "Arxiv"
year: 2024
bibkey: song2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.11629"}
tags: ['Attention Mechanism', 'Bias Mitigation', 'Ethics And Bias', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'RAG']
---
Leveraging Large Language Models (LLMs) as judges for judging the performance of LLMs has recently garnered attention. However this type of approach is affected by the potential biases in LLMs raising concerns about the reliability of the evaluation results. To mitigate this issue we propose and study two versions of many-shot in-context prompts which rely on two existing settings of many-shot ICL for helping GPT-4o-as-a-Judge in single answer grading to mitigate the potential biases in LLMs Reinforced ICL and Unsupervised ICL. Concretely the former utilizes in-context examples with model-generated rationales and the latter without. Based on the designed prompts we investigate the impact of scaling the number of in-context examples on the consistency and quality of the judgment results. Furthermore we reveal the symbol bias hidden in the pairwise comparison of GPT-4o-as-a-Judge and propose a simple yet effective approach to mitigate it. Experimental results show that advanced long-context LLMs such as GPT-4o perform better in the many-shot regime than in the zero-shot regime. Meanwhile the experimental results further verify the effectiveness of the symbol bias mitigation approach.
