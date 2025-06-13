---
layout: publication
title: 'CAIN: Hijacking Llm-humans Conversations Via A Two-stage Malicious System Prompt Generation And Refining Framework'
authors: Viet Pham, Thai Le
conference: "Arxiv"
year: 2025
bibkey: pham2025hijacking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.16888"}
tags: ['Responsible AI', 'Security', 'Tools', 'Reinforcement Learning', 'Prompting', 'Applications']
---
Large language models (LLMs) have advanced many applications, but are also known to be vulnerable to adversarial attacks. In this work, we introduce a novel security threat: hijacking AI-human conversations by manipulating LLMs' system prompts to produce malicious answers only to specific targeted questions (e.g., "Who should I vote for US President?", "Are Covid vaccines safe?"), while behaving benignly on others. This attack is detrimental as it can enable malicious actors to exercise large-scale information manipulation by spreading harmful but benign-looking system prompts online. To demonstrate such an attack, we develop CAIN, an algorithm that can automatically curate such harmful system prompts for a specific target question in a black-box setting or without the need to access the LLM's parameters. Evaluated on both open-source and commercial LLMs, CAIN demonstrates significant adversarial impact. In untargeted attacks or forcing LLMs to output incorrect answers, CAIN achieves up to 40% F1 degradation on targeted questions while preserving high accuracy on benign inputs. For targeted attacks or forcing LLMs to output specific harmful answers, CAIN achieves over 70% F1 scores on these targeted responses with minimal impact on benign questions. Our results highlight the critical need for enhanced robustness measures to safeguard the integrity and safety of LLMs in real-world applications. All source code will be publicly available.
