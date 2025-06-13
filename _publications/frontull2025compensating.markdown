---
layout: publication
title: 'Compensating For Data With Reasoning: Low-resource Machine Translation With Llms'
authors: Samuel Frontull, Thomas Ströhle
conference: "Arxiv"
year: 2025
bibkey: frontull2025compensating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.22293'}
tags: ['RAG', 'GPT', 'Applications', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
Large Language Models (LLMs) have demonstrated strong capabilities in multilingual machine translation, sometimes even outperforming traditional neural systems. However, previous research has highlighted the challenges of using LLMs, particularly with prompt engineering, for low-resource languages. In this work, we introduce Fragment-Shot Prompting, a novel in-context learning method that segments input and retrieves translation examples based on syntactic coverage, along with Pivoted Fragment-Shot, an extension that enables translation without direct parallel data. We evaluate these methods using GPT-3.5, GPT-4o, o1-mini, LLaMA-3.3, and DeepSeek-R1 for translation between Italian and two Ladin variants, revealing three key findings: (1) Fragment-Shot Prompting is effective for translating into and between the studied low-resource languages, with syntactic coverage positively correlating with translation quality; (2) Models with stronger reasoning abilities make more effective use of retrieved knowledge, generally produce better translations, and enable Pivoted Fragment-Shot to significantly improve translation quality between the Ladin variants; and (3) prompt engineering offers limited, if any, improvements when translating from a low-resource to a high-resource language, where zero-shot prompting already yields satisfactory results. We publicly release our code and the retrieval corpora.
