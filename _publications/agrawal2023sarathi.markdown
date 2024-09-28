---
layout: publication
title: SARATHI Efficient LLM Inference by Piggybacking Decodes with Chunked Prefills
authors: Agrawal Amey, Panwar Ashish, Mohan Jayashree, Kwatra Nipun, Gulavani Bhargav S., Ramjee Ramachandran
conference: "Arxiv"
year: 2023
bibkey: agrawal2023sarathi
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2308.16369"}
tags: ['ARXIV', 'GPT', 'LLM', 'Model Architecture', 'Prompt', 'RAG']
---
Large Language Model (LLM) inference consists of two distinct phases - prefill phase which processes the input prompt and decode phase which generates output tokens autoregressively. While the prefill phase effectively saturates GPU compute at small batch sizes the decode phase results in low compute utilization as it generates one token at a time per request. The varying prefill and decode times also lead to imbalance across micro-batches when using pipeline parallelism resulting in further inefficiency due to bubbles. We present SARATHI to address these challenges. SARATHI employs chunked-prefills which splits a prefill request into equal sized chunks and decode-maximal batching which constructs a batch using a single prefill chunk and populates the remaining slots with decodes. During inference the prefill chunk saturates GPU compute while the decode requests piggyback and cost up to an order of magnitude less compared to a decode-only batch. Chunked-prefills allows constructing multiple decode-maximal batches from a single prefill request maximizing coverage of decodes that can piggyback. Furthermore the uniform compute design of these batches ameliorates the imbalance between micro-batches significantly reducing pipeline bubbles. Our techniques yield significant improvements in inference performance across models and hardware. For the LLaMA-13B model on A6000 GPU SARATHI improves decode throughput by up to 10x and accelerates end-to-end throughput by up to 1.33x. For LLaMa-33B on A100 GPU we achieve 1.25x higher end-to-end-throughput and up to 4.25x higher decode throughput. When used with pipeline parallelism on GPT-3 SARATHI reduces bubbles by 6.29x resulting in an end-to-end throughput improvement of 1.91x.
