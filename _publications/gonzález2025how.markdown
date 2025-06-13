---
layout: publication
title: 'How Do Pre-trained Models Support Software Engineering? An Empirical Study In Hugging Face'
authors: Alexandra González, Xavier Franch, David Lo, Silverio Martínez-fernández
conference: "Arxiv"
year: 2025
bibkey: gonzález2025how
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2506.03013"}
tags: ['Tools', 'Applications', 'Language Modeling', 'Model Architecture', 'Reinforcement Learning', 'Attention Mechanism', 'Arxiv']
---
Open-Source Pre-Trained Models (PTMs) provide extensive resources for various Machine Learning (ML) tasks, yet these resources lack a classification tailored to Software Engineering (SE) needs. To address this gap, we derive a taxonomy encompassing 147 SE tasks and apply an SE-oriented classification to PTMs in a popular open-source ML repository, Hugging Face (HF). Our repository mining study began with a systematically gathered database of PTMs from the HF API, considering their model card descriptions and metadata, and the abstract of the associated arXiv papers. We confirmed SE relevance through multiple filtering steps: detecting outliers, identifying near-identical PTMs, and the use of Gemini 2.0 Flash, which was validated with five pilot studies involving three human annotators. This approach uncovered 2,205 SE PTMs. We find that code generation is the most common SE task among PTMs, primarily focusing on software implementation, while requirements engineering and software design activities receive limited attention. In terms of ML tasks, text generation dominates within SE PTMs. Notably, the number of SE PTMs has increased markedly since 2023 Q2. Our classification provides a solid foundation for future automated SE scenarios, such as the sampling and selection of suitable PTMs.
