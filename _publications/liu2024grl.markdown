---
layout: publication
title: 'Grl-prompt: Towards Knowledge Graph Based Prompt Optimization Via Reinforcement Learning'
authors: Yuze Liu, Tingjie Liu, Tiehua Zhang, Youhua Xia, Jinze Wang, Zhishu Shen, Jiong Jin, Fei Richard Yu
conference: "Arxiv"
year: 2024
bibkey: liu2024grl
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.14479"}
tags: ['Agentic', 'Efficiency and Optimization', 'Tools', 'Applications', 'RAG', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
Large language models (LLMs) have demonstrated impressive success in a wide
range of natural language processing (NLP) tasks due to their extensive general
knowledge of the world. Recent works discovered that the performance of LLMs is
heavily dependent on the input prompt. However, prompt engineering is usually
done manually in a trial-and-error fashion, which can be labor-intensive and
challenging in order to find the optimal prompts. To address these problems and
unleash the utmost potential of LLMs, we propose a novel LLMs-agnostic
framework for prompt optimization, namely GRL-Prompt, which aims to
automatically construct optimal prompts via reinforcement learning (RL) in an
end-to-end manner. To provide structured action/state representation for
optimizing prompts, we construct a knowledge graph (KG) that better encodes the
correlation between the user query and candidate in-context examples.
Furthermore, a policy network is formulated to generate the optimal action by
selecting a set of in-context examples in a rewardable order to construct the
prompt. Additionally, the embedding-based reward shaping is utilized to
stabilize the RL training process. The experimental results show that
GRL-Prompt outperforms recent state-of-the-art methods, achieving an average
increase of 0.10 in ROUGE-1, 0.07 in ROUGE-2, 0.07 in ROUGE-L, and 0.05 in
BLEU.
