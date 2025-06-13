---
layout: publication
title: 'Texttiger: Text-based Intelligent Generation With Entity Prompt Refinement For Text-to-image Generation'
authors: Shintaro Ozaki, Kazuki Hayashi, Yusuke Sakai, Jingun Kwon, Hidetaka Kamigaito, Katsuhiko Hayashi, Manabu Okumura, Taro Watanabe
conference: "Arxiv"
year: 2025
bibkey: ozaki2025text
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.18269'}
tags: ['Prompting', 'Interpretability and Explainability']
---
Generating images from prompts containing specific entities requires models
to retain as much entity-specific knowledge as possible. However, fully
memorizing such knowledge is impractical due to the vast number of entities and
their continuous emergence. To address this, we propose Text-based Intelligent
Generation with Entity prompt Refinement (TextTIGER), which augments knowledge
on entities included in the prompts and then summarizes the augmented
descriptions using Large Language Models (LLMs) to mitigate performance
degradation from longer inputs. To evaluate our method, we introduce WiT-Cub
(WiT with Captions and Uncomplicated Background-explanations), a dataset
comprising captions, images, and an entity list. Experiments on four image
generation models and five LLMs show that TextTIGER improves image generation
performance in standard metrics (IS, FID, and CLIPScore) compared to
caption-only prompts. Additionally, multiple annotators' evaluation confirms
that the summarized descriptions are more informative, validating LLMs' ability
to generate concise yet rich descriptions. These findings demonstrate that
refining prompts with augmented and summarized entity-related descriptions
enhances image generation capabilities. The code and dataset will be available
upon acceptance.
