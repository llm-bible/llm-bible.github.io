---
layout: publication
title: 'Intention Analysis Makes Llms A Good Jailbreak Defender'
authors: Yuqi Zhang, Liang Ding, Lefei Zhang, Dacheng Tao
conference: "Arxiv"
year: 2024
bibkey: zhang2024intention
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.06561"}
tags: ['Responsible AI', 'Security', 'Model Architecture', 'Reinforcement Learning', 'RAG', 'GPT', 'Prompting']
---
Aligning large language models (LLMs) with human values, particularly when
facing complex and stealthy jailbreak attacks, presents a formidable challenge.
Unfortunately, existing methods often overlook this intrinsic nature of
jailbreaks, which limits their effectiveness in such complex scenarios. In this
study, we present a simple yet highly effective defense strategy, i.e.,
Intention Analysis (\\(\mathbb\{IA\}\\)). \\(\mathbb\{IA\}\\) works by triggering LLMs'
inherent self-correct and improve ability through a two-stage process: 1)
analyzing the essential intention of the user input, and 2) providing final
policy-aligned responses based on the first round conversation. Notably,
\\(\mathbb\{IA\}\\) is an inference-only method, thus could enhance LLM safety
without compromising their helpfulness. Extensive experiments on varying
jailbreak benchmarks across a wide range of LLMs show that \\(\mathbb\{IA\}\\) could
consistently and significantly reduce the harmfulness in responses (averagely
-48.2% attack success rate). Encouragingly, with our \\(\mathbb\{IA\}\\), Vicuna-7B
even outperforms GPT-3.5 regarding attack success rate. We empirically
demonstrate that, to some extent, \\(\mathbb\{IA\}\\) is robust to errors in
generated intentions. Further analyses reveal the underlying principle of
\\(\mathbb\{IA\}\\): suppressing LLM's tendency to follow jailbreak prompts, thereby
enhancing safety.
