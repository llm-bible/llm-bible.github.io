---
layout: publication
title: Language Models As Black45;box Optimizers For Vision45;language Models
authors: Liu Shihong, Lin Zhiqiu, Yu Samuel, Lee Ryan, Ling Tiffany, Pathak Deepak, Ramanan Deva
conference: "Arxiv"
year: 2023
bibkey: liu2023language
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.05950"}
tags: ['Model Architecture', 'Prompting', 'RAG', 'Reinforcement Learning', 'Tools']
---
Vision45;language models (VLMs) pre45;trained on web45;scale datasets have demonstrated remarkable capabilities on downstream tasks when fine45;tuned with minimal data. However many VLMs rely on proprietary data and are not open45;source which restricts the use of white45;box approaches for fine45;tuning. As such we aim to develop a black45;box approach to optimize VLMs through natural language prompts thereby avoiding the need to access model parameters feature embeddings or even output logits. We propose employing chat45;based LLMs to search for the best text prompt for VLMs. Specifically we adopt an automatic hill45;climbing procedure that converges to an effective prompt by evaluating the performance of current prompts and asking LLMs to refine them based on textual feedback all within a conversational process without human45;in45;the45;loop. In a challenging 145;shot image classification setup our simple approach surpasses the white45;box continuous prompting method (CoOp) by an average of 1.537; across 11 datasets including ImageNet. Our approach also outperforms both human45;engineered and LLM45;generated prompts. We highlight the advantage of conversational feedback that incorporates both positive and negative prompts suggesting that LLMs can utilize the implicit gradient direction in textual feedback for a more efficient search. In addition we find that the text prompts generated through our strategy are not only more interpretable but also transfer well across different VLM architectures in a black45;box manner. Lastly we apply our framework to optimize the state45;of45;the45;art black45;box VLM (DALL45;E 3) for text45;to45;image generation prompt inversion and personalization.
