---
layout: publication
title: "GROVE: A Retrieval-augmented Complex Story Generation Framework With A Forest Of Evidence"
authors: Wen Zhihua, Tian Zhiliang, Wu Wei, Yang Yuxin, Shi Yanqi, Huang Zhen, Li Dongsheng
conference: "Arxiv"
year: 2023
bibkey: wen2023retrieval
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.05388"}
tags: ['Few Shot', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Conditional story generation is significant in human-machine interaction particularly in producing stories with complex plots. While Large language models (LLMs) perform well on multiple NLP tasks including story generation it is challenging to generate stories with both complex and creative plots. Existing methods often rely on detailed prompts to guide LLMs to meet target conditions which inadvertently restrict the creative potential of the generated stories. We argue that leveraging information from exemplary human-written stories facilitates generating more diverse plotlines. Delving deeper into story details helps build complex and credible plots. In this paper we propose a retrieval-au(textbfG)mented sto(textbfR)y generation framework with a f(textbfO)rest of e(textbfV)id(textbfE)nce (GROVE) to enhance stories complexity. We build a retrieval repository for target conditions to produce few-shot examples to prompt LLMs. Additionally we design an asking-why prompting scheme that extracts a forest of evidence providing compensation for the ambiguities that may occur in the generated story. This iterative process uncovers underlying story backgrounds. Finally we select the most fitting chains of evidence from the evidence forest and integrate them into the generated story thereby enhancing the narratives complexity and credibility. Experimental results and numerous examples verify the effectiveness of our method.
