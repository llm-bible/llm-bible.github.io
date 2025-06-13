---
layout: publication
title: 'Copyspec: Accelerating Llms With Speculative Copy-and-paste Without Compromising Quality'
authors: Razvan-gabriel Dumitru, Minglai Yang, Vikas Yadav, Mihai Surdeanu
conference: "Arxiv"
year: 2025
bibkey: dumitru2025accelerating
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2502.08923'}
  - {name: "Code", url: 'https://github.com/RazvanDu/CopySpec'}
tags: ['Reinforcement Learning', 'RAG', 'Has Code']
---
We introduce CopySpec, a simple yet effective technique to tackle the inefficiencies LLMs face when generating responses that closely resemble previous outputs or responses that can be verbatim extracted from context. CopySpec identifies repeated sequences in the model's chat history or context and speculates that the same tokens will follow, enabling seamless copying without compromising output quality and without requiring additional GPU memory. To evaluate the effectiveness of our approach, we conducted experiments using seven LLMs and five datasets: MT-Bench, CNN/DM, GSM8K, HumanEval, and our newly created dataset, MT-Redundant. MT-Redundant, introduced in this paper, transforms the second turn of MT-Bench into a request for variations of the first turn's answer, simulating real-world scenarios where users request modifications to prior responses. Our results demonstrate significant speed-ups: up to 2.35x on CNN/DM, 3.08x on the second turn of select MT-Redundant categories, and 2.66x on the third turn of GSM8K's self-correction tasks. Importantly, we show that CopySpec integrates seamlessly with speculative decoding, yielding an average 49% additional speed-up over speculative decoding for the second turn of MT-Redundant across all eight categories. While LLMs, even with speculative decoding, suffer from slower inference as context size grows, CopySpec leverages larger contexts to accelerate inference, making it a faster complementary solution. Our code and dataset are publicly available at https://github.com/RazvanDu/CopySpec.
