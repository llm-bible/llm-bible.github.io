---
layout: publication
title: Persona Is A Double45;edged Sword Enhancing The Zero45;shot Reasoning By Ensembling The Role45;playing And Neutral Prompts
authors: Kim Junseok, Yang Nakyeong, Jung Kyomin
conference: "Arxiv"
year: 2024
bibkey: kim2024persona
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.08631"}
tags: ['Ethics And Bias', 'GPT', 'Merging', 'Model Architecture', 'Prompting', 'Security', 'Tools']
---
Recent studies demonstrate that prompting an appropriate role45;playing persona to an LLM improves its reasoning capability. However assigning a proper persona is difficult since an LLMs performance is extremely sensitive to assigned prompts; therefore personas sometimes hinder LLMs and degrade their reasoning capabilities. In this paper we propose a novel framework Jekyll amp; Hyde which ensembles the results of role45;playing and neutral prompts to eradicate performance degradation via unilateral use of role45;playing prompted LLM and enhance the robustness of an LLMs reasoning ability. Specifically Jekyll amp; Hyde collects two potential solutions from both role45;playing and neutral prompts and selects a better solution after cross45;checking via an LLM evaluator. However LLM45;based evaluators tend to be affected by the order of those potential solutions within the prompt when selecting the proper solution; thus we also propose a robust LLM evaluator to mitigate the position bias. The experimental analysis demonstrates that role45;playing prompts distract LLMs and degrade their reasoning abilities in 4 out of 12 datasets even when using GPT45;4. In addition we reveal that Jekyll amp; Hyde improves reasoning capabilities by selecting better choices among the potential solutions on twelve widely45;used reasoning datasets. We further show that our proposed LLM evaluator outperforms other baselines proving the LLMs position bias is successfully mitigated.
