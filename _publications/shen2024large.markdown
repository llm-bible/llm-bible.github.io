---
layout: publication
title: 'Shortcutsbench: A Large-scale Real-world Benchmark For Api-based Agents'
authors: Haiyang Shen, Yue Li, Desong Meng, Dongqi Cai, Sheng Qi, Li Zhang, Mengwei Xu, Yun Ma
conference: "Arxiv"
year: 2024
bibkey: shen2024large
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2407.00132'}
  - {name: "Code", url: 'https://github.com/EachSheep/ShortcutsBench'}
tags: ['Agentic', 'Has Code', 'GPT', 'Tools', 'Model Architecture', 'Reinforcement Learning']
---
Recent advancements in integrating large language models (LLMs) with
application programming interfaces (APIs) have gained significant interest in
both academia and industry. Recent work demonstrates that these API-based
agents exhibit relatively strong autonomy and planning capabilities. However,
their ability to handle multi-dimensional difficulty levels, diverse task
types, and real-world demands remains unknown. In this paper, we introduce
\textsc\{ShortcutsBench\}, a large-scale benchmark for the comprehensive
evaluation of API-based agents in solving real-world complex tasks.
\textsc\{ShortcutsBench\} includes a wealth of real APIs from Apple Inc., refined
user queries, human-annotated high-quality action sequences, detailed parameter
filling values, and parameters requesting necessary input from the system or
user. We revealed how existing benchmarks~/~datasets struggle to accommodate
the advanced reasoning capabilities of existing more intelligent LLMs.
Moreover, our extensive evaluation of agents built with \\(5\\) leading open-source
(size \\(\geq\\) 57B) and \\(5\\) closed-source LLMs (e.g. Gemini-1.5-Pro and
GPT-4o-mini) with varying intelligence level reveals significant limitations of
existing API-based agents in the whole process of handling complex queries
related to API selection, parameter filling, and requesting necessary input
from the system and the user. These findings highlight the great challenges
that API-based agents face in effectively fulfilling real and complex user
queries. All datasets, code, experimental logs, and results are available at
\url\{https://github.com/EachSheep/ShortcutsBench\}.
