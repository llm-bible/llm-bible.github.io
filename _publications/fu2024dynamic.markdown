---
layout: publication
title: Lazyllm Dynamic Token Pruning For Efficient Long Context LLM Inference
authors: Fu Qichen, Cho Minsik, Merth Thomas, Mehta Sachin, Rastegari Mohammad, Najibi Mahyar
conference: "Arxiv"
year: 2024
bibkey: fu2024dynamic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.14057"}
tags: ['Efficiency And Optimization', 'Fine Tuning', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'Pruning', 'Training Techniques', 'Transformer']
---
The inference of transformer-based large language models consists of two sequential stages 1) a prefilling stage to compute the KV cache of prompts and generate the first token and 2) a decoding stage to generate subsequent tokens. For long prompts the KV cache must be computed for all tokens during the prefilling stage which can significantly increase the time needed to generate the first token. Consequently the prefilling stage may become a bottleneck in the generation process. An open question remains whether all prompt tokens are essential for generating the first token. To answer this we introduce a novel method LazyLLM that selectively computes the KV for tokens important for the next token prediction in both the prefilling and decoding stages. Contrary to static pruning approaches that prune the prompt at once LazyLLM allows language models to dynamically select different subsets of tokens from the context in different generation steps even though they might be pruned in previous steps. Extensive experiments on standard datasets across various tasks demonstrate that LazyLLM is a generic method that can be seamlessly integrated with existing language models to significantly accelerate the generation without fine-tuning. For instance in the multi-document question-answering task LazyLLM accelerates the prefilling stage of the LLama 2 7B model by 2.34x while maintaining accuracy.
