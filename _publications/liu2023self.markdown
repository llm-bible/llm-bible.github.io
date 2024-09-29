---
layout: publication
title: "Self-contradictory Reasoning Evaluation And Detection"
authors: Liu Ziyi, Lee Isabelle, Du Yongkang, Sanyal Soumya, Zhao Jieyu
conference: "Arxiv"
year: 2023
bibkey: liu2023self
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2311.09603"}
tags: ['Ethics And Bias', 'GPT', 'Model Architecture', 'Reinforcement Learning', 'Security']
---
In a plethora of recent work large language models (LLMs) demonstrated impressive reasoning ability but many proposed downstream reasoning tasks focus on performance-wise evaluation. Two fundamental questions persist 1) how reliable is the quality of reasoning and 2) can models detect unreliable reasoning In this paper we investigate self-contradictory (Self-Contra) reasoning where the model reasoning does not support predictions. To address 1) we assess the Self-Contra rate across four datasets and delve into finer-grained categories of Self-Contra reasoning. We find that LLMs often contradict themselves when performing reasoning tasks that involve contextual information understanding or commonsense. Importantly a higher accuracy does not necessarily correspond to a lower Self-Contra rate. The model may appear to generate correct answers but it may take shortcuts in reasoning or skip over contextual evidence thereby displaying Self-Contra behaviors with compromised reasoning. As for 2) we task GPT-4 with identifying Self-Contra reasoning and finer-grained fallacies. We observe that GPT-4 struggles to effectively detect Self-Contra reasoning with significantly low performance compared with human judgment. Our results indicate that the current LLMs lack robustness necessary for reliable reasoning and we emphasize the urgent need for establishing best practices in comprehensive reasoning evaluations beyond accuracy-based metrics.
