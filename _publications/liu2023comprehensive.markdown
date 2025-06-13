---
layout: publication
title: 'Nlebench+norglm: A Comprehensive Empirical Analysis And Benchmark Dataset For Generative Language Models In Norwegian'
authors: Peng Liu, Lemei Zhang, Terje Farup, Even W. Lauvrak, Jon Espen Ingvaldsen, Simen Eide, Jon Atle Gulla, Zhirong Yang
conference: "Arxiv"
year: 2023
bibkey: liu2023comprehensive
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2312.01314'}
tags: ['Training Techniques', 'Model Architecture', 'Applications', 'GPT', 'Pre-Training']
---
Norwegian, spoken by only 5 million population, is under-representative
within the most impressive breakthroughs in NLP tasks. To the best of our
knowledge, there has not yet been a comprehensive evaluation of the existing
language models (LMs) on Norwegian generation tasks during the article writing
process. To fill this gap, we 1) compiled the existing Norwegian dataset and
pre-trained 4 Norwegian Open Language Models varied from parameter scales and
architectures, collectively called NorGLM; 2) introduced a comprehensive
benchmark, NLEBench, for evaluating natural language generation capabilities in
Norwegian, encompassing translation and human annotation. Based on the
investigation, we find that: 1) the mainstream, English-dominated LM GPT-3.5
has limited capability in understanding the Norwegian context; 2) the increase
in model parameter scales demonstrates limited impact on the performance of
downstream tasks when the pre-training dataset is constrained in size; 3)
smaller models also demonstrate the reasoning capability through
Chain-of-Thought; 4) a multi-task dataset that includes synergy tasks can be
used to verify the generalizability of LLMs on natural language understanding
and, meanwhile, test the interconnectedness of these NLP tasks. We share our
resources and code for reproducibility under a CC BY-NC 4.0 license.
