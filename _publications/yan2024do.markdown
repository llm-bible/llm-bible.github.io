---
layout: publication
title: Do Large Language Models Understand Logic or Just mimic Context
authors: Yan Junbing, Wang Chengyu, Huang Jun, Zhang Wei
conference: "Arxiv"
year: 2024
bibkey: yan2024do
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.12091"}
tags: ['Attention Mechanism', 'Few Shot', 'In Context Learning', 'Model Architecture', 'Prompting']
---
Over the past few years the abilities of large language models (LLMs) have received extensive attention which have performed exceptionally well in complicated scenarios such as logical reasoning and symbolic inference. A significant factor contributing to this progress is the benefit of in-context learning and few-shot prompting. However the reasons behind the success of such models using contextual reasoning have not been fully explored. Do LLMs have understand logical rules to draw inferences or do they guess the answers by learning a type of probabilistic mapping through context This paper investigates the reasoning capabilities of LLMs on two logical reasoning datasets by using counterfactual methods to replace context text and modify logical concepts. Based on our analysis it is found that LLMs do not truly understand logical rules; rather in-context learning has simply enhanced the likelihood of these models arriving at the correct answers. If one alters certain words in the context text or changes the concepts of logical terms the outputs of LLMs can be significantly disrupted leading to counter-intuitive responses. This work provides critical insights into the limitations of LLMs underscoring the need for more robust mechanisms to ensure reliable logical reasoning in LLMs.
