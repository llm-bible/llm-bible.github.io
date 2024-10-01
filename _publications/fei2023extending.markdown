---
layout: publication
title: 'Extending Context Window Of Large Language Models Via Semantic Compression'
authors: Fei Weizhi, Niu Xueyan, Zhou Pingyi, Hou Lu, Bai Bo, Deng Lei, Han Wei
conference: "Arxiv"
year: 2023
bibkey: fei2023extending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.09571"}
tags: ['Applications', 'Few Shot', 'Fine Tuning', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Training Techniques', 'Transformer']
---
Transformer-based Large Language Models (LLMs) often impose limitations on the length of the text input to ensure the generation of fluent and relevant responses. This constraint restricts their applicability in scenarios involving long texts. We propose a novel semantic compression method that enables generalization to texts that are 6-8 times longer, without incurring significant computational costs or requiring fine-tuning. Our proposed framework draws inspiration from source coding in information theory and employs a pre-trained model to reduce the semantic redundancy of long inputs before passing them to the LLMs for downstream tasks. Experimental results demonstrate that our method effectively extends the context window of LLMs across a range of tasks including question answering, summarization, few-shot learning, and information retrieval. Furthermore, the proposed semantic compression method exhibits consistent fluency in text generation while reducing the associated computational overhead.
