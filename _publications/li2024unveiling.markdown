---
layout: publication
title: Perteval Unveiling Real Knowledge Capacity Of Llms With Knowledge45;invariant Perturbations
authors: Li Jiatong, Hu Renjun, Huang Kunzhe, Zhuang Yan, Liu Qi, Zhu Mengxiao, Shi Xing, Lin Wei
conference: "Arxiv"
year: 2024
bibkey: li2024unveiling
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.19740"}
tags: ['GPT', 'Model Architecture', 'Reinforcement Learning', 'Tools']
---
Expert45;designed close45;ended benchmarks serve as vital tools in assessing the knowledge capacity of large language models (LLMs). Despite their widespread use concerns have mounted regarding their reliability due to limited test scenarios and an unavoidable risk of data contamination. To rectify this we present PertEval a toolkit devised for in45;depth probing of LLMs knowledge capacity through knowledge45;invariant perturbations. These perturbations employ human45;like restatement techniques to generate on45;the45;fly test samples from static benchmarks meticulously retaining knowledge45;critical content while altering irrelevant details. Our toolkit further includes a suite of transition analyses that compare performance on raw vs. perturbed test sets to precisely assess LLMs genuine knowledge capacity. Six state45;of45;the45;art LLMs are re45;evaluated using PertEval. Results reveal significantly inflated performance of the LLMs on raw benchmarks including an absolute 2137; overestimation for GPT45;4. Additionally through a nuanced response pattern analysis we discover that PertEval retains LLMs uncertainty to specious knowledge potentially being resolved through rote memorization and leading to inflated performance. We also find that the detailed transition analyses by PertEval could illuminate weaknesses in existing LLMs knowledge mastery and guide the development of refinement. Given these insights we posit that PertEval can act as an essential tool that when applied alongside any close45;ended benchmark unveils the true knowledge capacity of LLMs marking a significant step toward more trustworthy LLM evaluation.
