---
layout: publication
title: 'Hallu-pi: Evaluating Hallucination In Multi-modal Large Language Models Within Perturbed Inputs'
authors: Ding Peng, Wu Jingyu, Kuang Jun, Ma Dan, Cao Xuezhi, Cai Xunliang, Chen Shi, Chen Jiajun, Huang Shujian
conference: "Arxiv"
year: 2024
bibkey: ding2024hallu
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2408.01355"}
  - {name: "Code", url: "https://github.com/NJUNLP/Hallu-PI"}
tags: ['Attention Mechanism', 'Ethics And Bias', 'GPT', 'Has Code', 'Model Architecture', 'Reinforcement Learning']
---
Multi-modal Large Language Models (MLLMs) have demonstrated remarkable performance on various visual-language understanding and generation tasks. However MLLMs occasionally generate content inconsistent with the given images which is known as hallucination. Prior works primarily center on evaluating hallucination using standard unperturbed benchmarks which overlook the prevalent occurrence of perturbed inputs in real-world scenarios-such as image cropping or blurring-that are critical for a comprehensive assessment of MLLMs hallucination. In this paper to bridge this gap we propose Hallu-PI the first benchmark designed to evaluate Hallucination in MLLMs within Perturbed Inputs. Specifically Hallu-PI consists of seven perturbed scenarios containing 1260 perturbed images from 11 object types. Each image is accompanied by detailed annotations which include fine-grained hallucination types such as existence attribute and relation. We equip these annotations with a rich set of questions making Hallu-PI suitable for both discriminative and generative tasks. Extensive experiments on 12 mainstream MLLMs such as GPT-4V and Gemini-Pro Vision demonstrate that these models exhibit significant hallucinations on Hallu-PI which is not observed in unperturbed scenarios. Furthermore our research reveals a severe bias in MLLMs ability to handle different types of hallucinations. We also design two baselines specifically for perturbed scenarios namely Perturbed-Reminder and Perturbed-ICL. We hope that our study will bring researchers attention to the limitations of MLLMs when dealing with perturbed inputs and spur further investigations to address this issue. Our code and datasets are publicly available at https://github.com/NJUNLP/Hallu-PI."
