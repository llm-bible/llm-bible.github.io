---
layout: publication
title: 'Enabling Efficient On-device Fine-tuning Of Llms Using Only Inference Engines'
authors: Lei Gao, Amir Ziashahabi, Yue Niu, Salman Avestimehr, Murali Annavaram
conference: "Arxiv"
year: 2024
bibkey: gao2024enabling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.15520"}
tags: ['Fine-Tuning', 'Efficiency and Optimization', 'Applications', 'RAG', 'Reinforcement Learning', 'Large-Scale Training', 'Training Techniques', 'Pretraining Methods']
---
Large Language Models (LLMs) are currently pre-trained and fine-tuned on
large cloud servers. The next frontier is LLM personalization, where a
foundation model can be fine-tuned with user/task-specific data. Given the
sensitive nature of such private data, it is desirable to fine-tune these
models on edge devices to improve user trust. However, fine-tuning on
resource-constrained edge devices presents significant challenges due to
substantial memory and computational demands, as well as limited infrastructure
support. We observe that inference engines (e.g., ExecuTorch) can be repurposed
for fine-tuning by leveraging zeroth-order (ZO) optimization, which uses
multiple forward passes to approximate gradients. However, directly applying ZO
methods on edge devices is impractical due to the high computational cost of
multiple model perturbations required to achieve accuracy improvements. Based
on these observations, we propose a memory- and computation-efficient LLM
fine-tuning method for edge devices. Our approach has three key innovations:
(1) We introduce a parallelized randomized gradient estimation (P-RGE)
technique that achieves high parallel efficiency by leveraging outer-loop and
inner-loop parallelization. This enables multiple function queries and forward
passes to be executed in parallel, reducing training time. (2) We integrate
P-RGE with parameter-efficient fine-tuning methods (e.g. LoRA) to further
reduce computational and memory overhead. (3) We implement a P-RGE LoRA-FA
module that fully supports fine-tuning with ExecuTorch. Our approach requires
no modifications to ExecuTorch's runtime code, as it can be implemented with
server-side code changes only. Experiments demonstrate that P-RGE achieves
substantial runtime speedups and memory savings while improving fine-tuning
accuracy, paving the way for practical deployment of LLMs in real-time,
on-device applications.
