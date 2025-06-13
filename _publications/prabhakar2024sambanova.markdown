---
layout: publication
title: 'Sambanova SN40L: Scaling The AI Memory Wall With Dataflow And Composition Of Experts'
authors: Raghu Prabhakar, Ram Sivaramakrishnan, Darshan Gandhi, Yun Du, Mingran Wang, Xiangyu Song, Kejie Zhang, Tianren Gao, Angela Wang, Karen Li, Yongning Sheng, Joshua Brot, Denis Sokolov, Apurv Vivek, Calvin Leung, Arjun Sabnis, Jiayu Bai, Tuowen Zhao, Mark Gottscho, David Jackson, Mark Luttrell, Manish K. Shah, Edison Chen, Kaizhao Liang, Swayambhoo Jain, Urmish Thakker, Dawei Huang, Sumti Jairath, Kevin J. Brown, Kunle Olukotun
conference: "Arxiv"
year: 2024
bibkey: prabhakar2024sambanova
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2405.07518'}
tags: ['Training Techniques', 'Model Architecture', 'Applications', 'GPT']
---
Monolithic large language models (LLMs) like GPT-4 have paved the way for
modern generative AI applications. Training, serving, and maintaining
monolithic LLMs at scale, however, remains prohibitively expensive and
challenging. The disproportionate increase in compute-to-memory ratio of modern
AI accelerators have created a memory wall, necessitating new methods to deploy
AI. Composition of Experts (CoE) is an alternative modular approach that lowers
the cost and complexity of training and serving. However, this approach
presents two key challenges when using conventional hardware: (1) without fused
operations, smaller models have lower operational intensity, which makes high
utilization more challenging to achieve; and (2) hosting a large number of
models can be either prohibitively expensive or slow when dynamically switching
between them.
  In this paper, we describe how combining CoE, streaming dataflow, and a
three-tier memory system scales the AI memory wall. We describe Samba-CoE, a
CoE system with 150 experts and a trillion total parameters. We deploy
Samba-CoE on the SambaNova SN40L Reconfigurable Dataflow Unit (RDU) - a
commercial dataflow accelerator architecture that has been co-designed for
enterprise inference and training applications. The chip introduces a new
three-tier memory system with on-chip distributed SRAM, on-package HBM, and
off-package DDR DRAM. A dedicated inter-RDU network enables scaling up and out
over multiple sockets. We demonstrate speedups ranging from 2\\(\times\\) to
13\\(\times\\) on various benchmarks running on eight RDU sockets compared with an
unfused baseline. We show that for CoE inference deployments, the 8-socket RDU
Node reduces machine footprint by up to 19\\(\times\\), speeds up model switching
time by 15\\(\times\\) to 31\\(\times\\), and achieves an overall speedup of
3.7\\(\times\\) over a DGX H100 and 6.6\\(\times\\) over a DGX A100.
