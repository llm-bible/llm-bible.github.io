---
layout: publication
title: ""my Answer Is C": First-token Probabilities Do Not Match Text Answers In Instruction-tuned Language Models"
authors: Wang Xinpeng, Ma Bolei, Hu Chengzhi, Weber-genzel Leon, Röttger Paul, Kreuter Frauke, Hovy Dirk, Plank Barbara
conference: "Arxiv"
year: 2024
bibkey: wang2024answer
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.14499"}
tags: ['GPT', 'Pretraining Methods', 'Prompting', 'Responsible AI', 'Security']
---
The open-ended nature of language generation makes the evaluation of autoregressive large language models (LLMs) challenging. One common evaluation approach uses multiple-choice questions (MCQ) to limit the response space. The model is then evaluated by ranking the candidate answers by the log probability of the first token prediction. However first-tokens may not consistently reflect the final response output due to models diverse response styles such as starting with Sure or refusing to answer. Consequently MCQ evaluation is not indicative of model behaviour when interacting with users. But by how much We evaluate how aligned first-token evaluation is with the text output along several dimensions namely final option choice refusal rate choice distribution and robustness under prompt perturbation. Our results show that the two approaches are severely misaligned on all dimensions reaching mismatch rates over 6037;. Models heavily fine-tuned on conversational or safety data are especially impacted. Crucially models remain misaligned even when we increasingly constrain prompts i.e. force them to start with an option letter or example template. Our findings i) underscore the importance of inspecting the text output as well and ii) caution against relying solely on first-token evaluation.
