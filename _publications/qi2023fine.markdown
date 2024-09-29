---
layout: publication
title: Fine45;tuning Aligned Language Models Compromises Safety Even When Users Do Not Intend To!
authors: Qi Xiangyu, Zeng Yi, Xie Tinghao, Chen Pin-yu, Jia Ruoxi, Mittal Prateek, Henderson Peter
conference: "Arxiv"
year: 2023
bibkey: qi2023fine
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.03693"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Responsible AI', 'Security', 'Tools', 'Training Techniques']
---
Optimizing large language models (LLMs) for downstream use cases often involves the customization of pre45;trained LLMs through further fine45;tuning. Metas open release of Llama models and OpenAIs APIs for fine45;tuning GPT45;3.5 Turbo on custom datasets also encourage this practice. But what are the safety costs associated with such custom fine45;tuning We note that while existing safety alignment infrastructures can restrict harmful behaviors of LLMs at inference time they do not cover safety risks when fine45;tuning privileges are extended to end45;users. Our red teaming studies find that the safety alignment of LLMs can be compromised by fine45;tuning with only a few adversarially designed training examples. For instance we jailbreak GPT45;3.5 Turbos safety guardrails by fine45;tuning it on only 10 such examples at a cost of less than 0.20 via OpenAIs APIs making the model responsive to nearly any harmful instructions. Disconcertingly our research also reveals that even without malicious intent simply fine45;tuning with benign and commonly used datasets can also inadvertently degrade the safety alignment of LLMs though to a lesser extent. These findings suggest that fine45;tuning aligned LLMs introduces new safety risks that current safety infrastructures fall short of addressing 45;45; even if a models initial safety alignment is impeccable it is not necessarily to be maintained after custom fine45;tuning. We outline and critically analyze potential mitigations and advocate for further research efforts toward reinforcing safety protocols for the custom fine45;tuning of aligned LLMs.
