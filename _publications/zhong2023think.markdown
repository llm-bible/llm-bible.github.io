---
layout: publication
title: 'Let''s Think Outside The Box: Exploring Leap-of-thought In Large Language Models With Creative Humor Generation'
authors: Shanshan Zhong, Zhongzhan Huang, Shanghua Gao, Wushao Wen, Liang Lin, Marinka Zitnik, Pan Zhou
conference: "Arxiv"
year: 2023
bibkey: zhong2023think
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.02439"}
  - {name: "Code", url: "https://zhongshsh.github.io/CLoT/"}
tags: ['Multimodal Models', 'RAG', 'Fine-Tuning', 'Has Code', 'Applications']
---
Chain-of-Thought (CoT) guides large language models (LLMs) to reason
step-by-step, and can motivate their logical reasoning ability. While effective
for logical tasks, CoT is not conducive to creative problem-solving which often
requires out-of-box thoughts and is crucial for innovation advancements. In
this paper, we explore the Leap-of-Thought (LoT) abilities within LLMs -- a
non-sequential, creative paradigm involving strong associations and knowledge
leaps. To this end, we study LLMs on the popular Oogiri game which needs
participants to have good creativity and strong associative thinking for
responding unexpectedly and humorously to the given image, text, or both, and
thus is suitable for LoT study. Then to investigate LLMs' LoT ability in the
Oogiri game, we first build a multimodal and multilingual Oogiri-GO dataset
which contains over 130,000 samples from the Oogiri game, and observe the
insufficient LoT ability or failures of most existing LLMs on the Oogiri game.
Accordingly, we introduce a creative Leap-of-Thought (CLoT) paradigm to improve
LLM's LoT ability. CLoT first formulates the Oogiri-GO dataset into
LoT-oriented instruction tuning data to train pretrained LLM for achieving
certain LoT humor generation and discrimination abilities. Then CLoT designs an
explorative self-refinement that encourages the LLM to generate more creative
LoT data via exploring parallels between seemingly unrelated concepts and
selects high-quality data to train itself for self-refinement. CLoT not only
excels in humor generation in the Oogiri game but also boosts creative
abilities in various tasks like cloud guessing game and divergent association
task. These findings advance our understanding and offer a pathway to improve
LLMs' creative capacities for innovative applications across domains. The
dataset, code, and models will be released online.
https://zhongshsh.github.io/CLoT/.
