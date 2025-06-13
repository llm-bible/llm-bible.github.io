---
layout: publication
title: 'Trapping LLM Hallucinations Using Tagged Context Prompts'
authors: Philip Feldman, James R. Foulds, Shimei Pan
conference: "Arxiv"
year: 2023
bibkey: feldman2023trapping
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.06085"}
tags: ['Agentic', 'Model Architecture', 'Tools', 'Reinforcement Learning', 'GPT', 'Prompting']
---
Recent advances in large language models (LLMs), such as ChatGPT, have led to
highly sophisticated conversation agents. However, these models suffer from
"hallucinations," where the model generates false or fabricated information.
Addressing this challenge is crucial, particularly with AI-driven platforms
being adopted across various sectors. In this paper, we propose a novel method
to recognize and flag instances when LLMs perform outside their domain
knowledge, and ensuring users receive accurate information.
  We find that the use of context combined with embedded tags can successfully
combat hallucinations within generative language models. To do this, we
baseline hallucination frequency in no-context prompt-response pairs using
generated URLs as easily-tested indicators of fabricated data. We observed a
significant reduction in overall hallucination when context was supplied along
with question prompts for tested generative engines. Lastly, we evaluated how
placing tags within contexts impacted model responses and were able to
eliminate hallucinations in responses with 98.88% effectiveness.
