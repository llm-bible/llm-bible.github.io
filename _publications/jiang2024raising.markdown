---
layout: publication
title: 'Raising The Bar: Investigating The Values Of Large Language Models Via Generative Evolving Testing'
authors: Jiang Han, Yi Xiaoyuan, Wei Zhihua, Wang Shu, Xie Xing
conference: "Arxiv"
year: 2024
bibkey: jiang2024raising
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.14230"}
tags: ['Ethics And Bias', 'Reinforcement Learning', 'Responsible AI', 'Tools']
---
Warning: this paper contains model outputs exhibiting unethical information.
Large Language Models (LLMs) have achieved significant breakthroughs, but their
generated unethical content poses potential risks. Measuring value alignment of
LLMs becomes crucial for their regulation and responsible deployment. Numerous
datasets have been constructed to assess social bias, toxicity, and ethics in
LLMs, but they suffer from evaluation chronoeffect, that is, as models rapidly
evolve, existing data becomes leaked or undemanding, overestimating
ever-developing LLMs. To tackle this problem, we propose GETA, a novel
generative evolving testing approach that dynamically probes the underlying
moral baselines of LLMs. Distinct from previous adaptive testing methods that
rely on static datasets with limited difficulty, GETA incorporates an
iteratively-updated item generator which infers each LLM's moral boundaries and
generates difficulty-tailored testing items, accurately reflecting the true
alignment extent. This process theoretically learns a joint distribution of
item and model response, with item difficulty and value conformity as latent
variables, where the generator co-evolves with the LLM, addressing
chronoeffect. We evaluate various popular LLMs with diverse capabilities and
demonstrate that GETA can create difficulty-matching testing items and more
accurately assess LLMs' values, better consistent with their performance on
unseen OOD and i.i.d. items, laying the groundwork for future evaluation
paradigms.
