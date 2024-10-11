---
layout: publication
title: 'Perteval: Unveiling Real Knowledge Capacity Of Llms With Knowledge-invariant Perturbations'
authors: Li Jiatong, Hu Renjun, Huang Kunzhe, Zhuang Yan, Liu Qi, Zhu Mengxiao, Shi Xing, Lin Wei
conference: "Arxiv"
year: 2024
bibkey: li2024unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19740"}
tags: ['GPT', 'Model Architecture', 'Tools', 'Uncategorized']
---
Expert-designed close-ended benchmarks serve as vital tools in assessing the knowledge capacity of large language models (LLMs). Despite their widespread use, concerns have mounted regarding their reliability due to limited test scenarios and an unavoidable risk of data contamination. To rectify this, we present PertEval, a toolkit devised for in-depth probing of LLMs' knowledge capacity through knowledge-invariant perturbations. These perturbations employ human-like restatement techniques to generate on-the-fly test samples from static benchmarks, meticulously retaining knowledge-critical content while altering irrelevant details. Our toolkit further includes a suite of transition analyses that compare performance on raw vs. perturbed test sets to precisely assess LLMs' genuine knowledge capacity. Six state-of-the-art LLMs are re-evaluated using PertEval. Results reveal significantly inflated performance of the LLMs on raw benchmarks, including an absolute 21&#37; overestimation for GPT-4. Additionally, through a nuanced response pattern analysis, we discover that PertEval retains LLMs' uncertainty to specious knowledge, potentially being resolved through rote memorization and leading to inflated performance. We also find that the detailed transition analyses by PertEval could illuminate weaknesses in existing LLMs' knowledge mastery and guide the development of refinement. Given these insights, we posit that PertEval can act as an essential tool that, when applied alongside any close-ended benchmark, unveils the true knowledge capacity of LLMs, marking a significant step toward more trustworthy LLM evaluation.
