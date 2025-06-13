---
layout: publication
title: 'A Stitch In Time Saves Nine: Small VLM Is A Precise Guidance For Accelerating Large Vlms'
authors: Wangbo Zhao, Yizeng Han, Jiasheng Tang, Zhikai Li, Yibing Song, Kai Wang, Zhangyang Wang, Yang You
conference: "Arxiv"
year: 2024
bibkey: zhao2024stitch
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.03324"}
tags: ['Efficiency and Optimization', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'Reinforcement Learning', 'Pruning', 'Attention Mechanism']
---
Vision-language models (VLMs) have shown remarkable success across various
multi-modal tasks, yet large VLMs encounter significant efficiency challenges
due to processing numerous visual tokens. A promising approach to accelerating
large VLM inference is using partial information, such as attention maps from
specific layers, to assess token importance and prune less essential tokens.
However, our study reveals three key insights: (i) Partial attention
information is insufficient for accurately identifying critical visual tokens,
resulting in suboptimal performance, especially at low token retention ratios;
(ii) Global attention information, such as the attention map aggregated across
all layers, more effectively preserves essential tokens and maintains
comparable performance under aggressive pruning. However, the attention maps
from all layers requires a full inference pass, which increases computational
load and is therefore impractical in existing methods; and (iii) The global
attention map aggregated from a small VLM closely resembles that of a large
VLM, suggesting an efficient alternative. Based on these findings, we introduce
a \textbf\{training-free\} method, \underline\{\textbf\{S\}\}mall VLM
\underline\{\textbf\{G\}\}uidance for accelerating \underline\{\textbf\{L\}\}arge VLMs
(\textbf\{SGL\}). Specifically, we employ the attention map aggregated from a
small VLM to guide visual token pruning in a large VLM. Additionally, an early
exiting mechanism is developed to fully use the small VLM's predictions,
dynamically invoking the larger VLM only when necessary, yielding a superior
trade-off between accuracy and computation. Extensive evaluations across 11
benchmarks demonstrate the effectiveness and generalizability of SGL, achieving
up to 91% pruning ratio for visual tokens while retaining competitive
performance.
