---
layout: publication
title: 'Enhancing Sequential Recommendations Through Multi-perspective Reflections And Iteration'
authors: Weicong Qin, Yi Xu, Weijie Yu, Chenglei Shen, Xiao Zhang, Ming He, Jianping Fan, Jun Xu
conference: "Arxiv"
year: 2024
bibkey: qin2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.06377"}
tags: ['Training Techniques', 'Tools', 'Reinforcement Learning', 'RAG', 'Pretraining Methods', 'Fine-Tuning', 'Prompting']
---
Sequence recommendation (SeqRec) aims to predict the next item a user will
interact with by understanding user intentions and leveraging collaborative
filtering information. Large language models (LLMs) have shown great promise in
recommendation tasks through prompt-based, fixed reflection libraries, and
fine-tuning techniques. However, these methods face challenges, including lack
of supervision, inability to optimize reflection sources, inflexibility to
diverse user needs, and high computational costs. Despite promising results,
current studies primarily focus on reflections of users' explicit preferences
(e.g., item titles) while neglecting implicit preferences (e.g., brands) and
collaborative filtering information. This oversight hinders the capture of
preference shifts and dynamic user behaviors. Additionally, existing approaches
lack mechanisms for reflection evaluation and iteration, often leading to
suboptimal recommendations. To address these issues, we propose the Mixture of
REflectors (MoRE) framework, designed to model and learn dynamic user
preferences in SeqRec. Specifically, MoRE introduces three reflectors for
generating LLM-based reflections on explicit preferences, implicit preferences,
and collaborative signals. Each reflector incorporates a self-improving
strategy, termed refining-and-iteration, to evaluate and iteratively update
reflections. Furthermore, a meta-reflector employs a contextual bandit
algorithm to select the most suitable expert and corresponding reflections for
each user's recommendation, effectively capturing dynamic preferences.
Extensive experiments on three real-world datasets demonstrate that MoRE
consistently outperforms state-of-the-art methods, requiring less training time
and GPU memory compared to other LLM-based approaches in SeqRec.
