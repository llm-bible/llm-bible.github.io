---
layout: publication
title: Extending Context Window Of Large Language Models Via Semantic Compression
authors: Fei Weizhi, Niu Xueyan, Zhou Pingyi, Hou Lu, Bai Bo, Deng Lei, Han Wei
conference: "Arxiv"
year: 2023
bibkey: fei2023extending
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2312.09571"}
tags: ['Applications', 'Language Modeling', 'Model Architecture', 'Pretraining Methods', 'Tools', 'Transformer']
---
Transformer45;based Large Language Models (LLMs) often impose limitations on the length of the text input to ensure the generation of fluent and relevant responses. This constraint restricts their applicability in scenarios involving long texts. We propose a novel semantic compression method that enables generalization to texts that are 645;8 times longer without incurring significant computational costs or requiring fine45;tuning. Our proposed framework draws inspiration from source coding in information theory and employs a pre45;trained model to reduce the semantic redundancy of long inputs before passing them to the LLMs for downstream tasks. Experimental results demonstrate that our method effectively extends the context window of LLMs across a range of tasks including question answering summarization few45;shot learning and information retrieval. Furthermore the proposed semantic compression method exhibits consistent fluency in text generation while reducing the associated computational overhead.
