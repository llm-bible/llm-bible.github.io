---
layout: publication
title: 'PPT: A Process-based Preference Learning Framework For Self Improving Table Question Answering Models'
authors: Wei Zhou, Mohsen Mesgar, Heike Adel, Annemarie Friedrich
conference: "Arxiv"
year: 2025
bibkey: zhou2025process
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.17565"}
tags: ['Fine-Tuning', 'Tools', 'Applications']
---
Improving large language models (LLMs) with self-generated data has demonstrated success in tasks such as mathematical reasoning and code generation. Yet, no exploration has been made on table question answering (TQA), where a system answers questions based on tabular data. Addressing this gap is crucial for TQA, as effective self-improvement can boost performance without requiring costly or manually annotated data. In this work, we propose PPT, a Process-based Preference learning framework for TQA. It decomposes reasoning chains into discrete states, assigns scores to each state, and samples contrastive steps for preference learning. Experimental results show that PPT effectively improves TQA models by up to 5% on in-domain datasets and 2.4% on out-of-domain datasets, with only 8,000 preference pairs. Furthermore, the resulting models achieve competitive results compared to more complex and larger state-of-the-art TQA systems, while being five times more efficient during inference.
