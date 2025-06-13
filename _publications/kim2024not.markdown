---
layout: publication
title: 'Not All Options Are Created Equal: Textual Option Weighting For Token-efficient Llm-based Knowledge Tracing'
authors: Jongwoo Kim, Seongyeub Chu, Bryan Wong, Mun Yi
conference: "Arxiv"
year: 2024
bibkey: kim2024not
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.12872"}
  - {name: "Code", url: "https://anonymous.4open.science/r/LOKT_model-3233}{https://anonymous.4open.science/r/LOKT\_model-3233"}
tags: ['Tools', 'Interpretability and Explainability', 'Has Code', 'Prompting', 'In-Context Learning']
---
Large Language Models (LLMs) have recently emerged as promising tools for knowledge tracing (KT) due to their strong reasoning and generalization abilities. While recent LLM-based KT methods have proposed new prompt formats, they struggle to represent the full interaction histories of example learners within a single prompt during in-context learning (ICL), resulting in limited scalability and high computational cost under token constraints. In this work, we present \textit\{LLM-based Option-weighted Knowledge Tracing (LOKT)\}, a simple yet effective framework that encodes the interaction histories of example learners in context as \textit\{textual categorical option weights (TCOW)\}. TCOW are semantic labels (e.g., ``inadequate'') assigned to the options selected by learners when answering questions, enhancing the interpretability of LLMs. Experiments on multiple-choice datasets show that LOKT outperforms existing non-LLM and LLM-based KT models in both cold-start and warm-start settings. Moreover, LOKT enables scalable and cost-efficient inference, achieving strong performance even under strict token constraints. Our code is available at \href\{https://anonymous.4open.science/r/LOKT_model-3233\}\{https://anonymous.4open.science/r/LOKT\_model-3233\}.
