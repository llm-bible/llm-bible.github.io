---
layout: publication
title: 'Dynamic Uncertainty Ranking: Enhancing Retrieval-augmented In-context Learning For Long-tail Knowledge In Llms'
authors: Shuyang Yu, Runxue Bao, Parminder Bhatia, Taha Kass-hout, Jiayu Zhou, Cao Xiao
conference: "Arxiv"
year: 2024
bibkey: yu2024dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.23605"}
tags: ['Agentic', 'Efficiency and Optimization', 'Training Techniques', 'Reinforcement Learning', 'RAG', 'Prompting', 'Pre-Training', 'In-Context Learning']
---
Large language models (LLMs) can learn vast amounts of knowledge from diverse
domains during pre-training. However, long-tail knowledge from specialized
domains is often scarce and underrepresented, rarely appearing in the models'
memorization. Prior work has shown that in-context learning (ICL) with
retriever augmentation can help LLMs better capture long-tail knowledge,
reducing their reliance on pre-trained data. Despite these advances, we observe
that LLM predictions for long-tail questions remain uncertain to variations in
retrieved samples. To take advantage of the uncertainty in ICL for guiding LLM
predictions toward correct answers on long-tail samples, we propose a
reinforcement learning-based dynamic uncertainty ranking method for ICL that
accounts for the varying impact of each retrieved sample on LLM predictions.
Our approach prioritizes more informative and stable samples while demoting
misleading ones, updating rankings based on the feedback from the LLM w.r.t.
each retrieved sample. To enhance training efficiency and reduce query costs,
we introduce a learnable dynamic ranking threshold, adjusted when the model
encounters negative prediction shifts. Experimental results on various
question-answering datasets from different domains show that our method
outperforms the best baseline by \\(2.76%\\), with a notable \\(5.96%\\) boost in
accuracy on long-tail questions that elude zero-shot inference.
