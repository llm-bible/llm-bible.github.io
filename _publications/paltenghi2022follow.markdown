---
layout: publication
title: 'Follow-up Attention: An Empirical Study Of Developer And Neural Model Code Exploration'
authors: Paltenghi Matteo, Pandita Rahul, Henley Austin Z., Ziegler Albert
conference: "Arxiv"
year: 2022
bibkey: paltenghi2022follow
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.05506"}
tags: ['Applications', 'Attention Mechanism', 'Fine Tuning', 'GPT', 'Model Architecture', 'RAG', 'Reinforcement Learning', 'Transformer']
---
Recent neural models of code, such as OpenAI Codex and AlphaCode, have demonstrated remarkable proficiency at code generation due to the underlying attention mechanism. However, it often remains unclear how the models actually process code, and to what extent their reasoning and the way their attention mechanism scans the code matches the patterns of developers. A poor understanding of the model reasoning process limits the way in which current neural models are leveraged today, so far mostly for their raw prediction. To fill this gap, this work studies how the processed attention signal of three open large language models - CodeGen, InCoder and GPT-J - agrees with how developers look at and explore code when each answers the same sensemaking questions about code. Furthermore, we contribute an open-source eye-tracking dataset comprising 92 manually-labeled sessions from 25 developers engaged in sensemaking tasks. We empirically evaluate five heuristics that do not use the attention and ten attention-based post-processing approaches of the attention signal of CodeGen against our ground truth of developers exploring code, including the novel concept of follow-up attention which exhibits the highest agreement between model and human attention. Our follow-up attention method can predict the next line a developer will look at with 47&#37; accuracy. This outperforms the baseline prediction accuracy of 42.3&#37;, which uses the session history of other developers to recommend the next line. These results demonstrate the potential of leveraging the attention signal of pre-trained models for effective code exploration.
