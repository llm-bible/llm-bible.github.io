---
layout: publication
title: 'Thinkrec: Thinking-based Recommendation Via LLM'
authors: Qihang Yu, Kairui Fu, Shengyu Zhang, Zheqi Lv, Fan Wu, Fei Wu
conference: "Arxiv"
year: 2025
bibkey: yu2025thinking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.15091"}
  - {name: "Code", url: "https://github.com/Yu-Qi-hang/ThinkRec"}
tags: ['Tools', 'Reinforcement Learning', 'Merging', 'Has Code', 'Interpretability and Explainability', 'Applications']
---
Recent advances in large language models (LLMs) have enabled more semantic-aware recommendations through natural language generation. Existing LLM for recommendation (LLM4Rec) methods mostly operate in a System 1-like manner, relying on superficial features to match similar items based on click history, rather than reasoning through deeper behavioral logic. This often leads to superficial and erroneous recommendations. Motivated by this, we propose ThinkRec, a thinking-based framework that shifts LLM4Rec from System 1 to System 2 (rational system). Technically, ThinkRec introduces a thinking activation mechanism that augments item metadata with keyword summarization and injects synthetic reasoning traces, guiding the model to form interpretable reasoning chains that consist of analyzing interaction histories, identifying user preferences, and making decisions based on target items. On top of this, we propose an instance-wise expert fusion mechanism to reduce the reasoning difficulty. By dynamically assigning weights to expert models based on users' latent features, ThinkRec adapts its reasoning path to individual users, thereby enhancing precision and personalization. Extensive experiments on real-world datasets demonstrate that ThinkRec significantly improves the accuracy and interpretability of recommendations. Our implementations are available in anonymous Github: https://github.com/Yu-Qi-hang/ThinkRec.
