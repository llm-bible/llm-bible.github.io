---
layout: publication
title: Position Towards Implicit Prompt For Text-to-image Models
authors: Yang Yue, Lin Yuqi, Liu Hong, Shao Wenqi, Chen Runjian, Shang Hailong, Wang Yu, Qiao Yu, Zhang Kaipeng, Luo Ping
conference: "Arxiv"
year: 2024
bibkey: yang2024position
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.02118"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Prompting', 'Responsible AI']
---
Recent text-to-image (T2I) models have had great success and many benchmarks have been proposed to evaluate their performance and safety. However they only consider explicit prompts while neglecting implicit prompts (hint at a target without explicitly mentioning it). These prompts may get rid of safety constraints and pose potential threats to the applications of these models. This position paper highlights the current state of T2I models toward implicit prompts. We present a benchmark named ImplicitBench and conduct an investigation on the performance and impacts of implicit prompts with popular T2I models. Specifically we design and collect more than 2000 implicit prompts of three aspects General Symbols Celebrity Privacy and Not-Safe-For-Work (NSFW) Issues and evaluate six well-known T2I models capabilities under these implicit prompts. Experiment results show that (1) T2I models are able to accurately create various target symbols indicated by implicit prompts; (2) Implicit prompts bring potential risks of privacy leakage for T2I models. (3) Constraints of NSFW in most of the evaluated T2I models can be bypassed with implicit prompts. We call for increased attention to the potential and risks of implicit prompts in the T2I community and further investigation into the capabilities and impacts of implicit prompts advocating for a balanced approach that harnesses their benefits while mitigating their risks.
