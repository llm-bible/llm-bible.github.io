---
layout: publication
title: 'Embodied Executable Policy Learning With Language-based Scene Summarization'
authors: Jielin Qiu, Mengdi Xu, William Han, Seungwhan Moon, Ding Zhao
conference: "Arxiv"
year: 2023
bibkey: qiu2023embodied
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2306.05696"}
tags: ['Fine-Tuning', 'Agentic', 'Applications', 'Reinforcement Learning', 'ACL', 'Training Techniques', 'Pretraining Methods']
---
Large Language models (LLMs) have shown remarkable success in assisting robot
learning tasks, i.e., complex household planning. However, the performance of
pretrained LLMs heavily relies on domain-specific templated text data, which
may be infeasible in real-world robot learning tasks with image-based
observations. Moreover, existing LLMs with text inputs lack the capability to
evolve with non-expert interactions with environments. In this work, we
introduce a novel learning paradigm that generates robots' executable actions
in the form of text, derived solely from visual observations, using
language-based summarization of these observations as the connecting bridge
between both domains. Our proposed paradigm stands apart from previous works,
which utilized either language instructions or a combination of language and
visual data as inputs. Moreover, our method does not require oracle text
summarization of the scene, eliminating the need for human involvement in the
learning loop, which makes it more practical for real-world robot learning
tasks. Our proposed paradigm consists of two modules: the SUM module, which
interprets the environment using visual observations and produces a text
summary of the scene, and the APM module, which generates executable action
policies based on the natural language descriptions provided by the SUM module.
We demonstrate that our proposed method can employ two fine-tuning strategies,
including imitation learning and reinforcement learning approaches, to adapt to
the target test tasks effectively. We conduct extensive experiments involving
various SUM/APM model selections, environments, and tasks across 7 house
layouts in the VirtualHome environment. Our experimental results demonstrate
that our method surpasses existing baselines, confirming the effectiveness of
this novel learning paradigm.
