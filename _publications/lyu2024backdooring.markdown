---
layout: publication
title: 'Backdooring Vision-language Models With Out-of-distribution Data'
authors: Weimin Lyu, Jiachen Yao, Saumya Gupta, Lu Pang, Tao Sun, Lingjie Yi, Lijie Hu, Haibin Ling, Chao Chen
conference: "Arxiv"
year: 2024
bibkey: lyu2024backdooring
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.01264"}
tags: ['Applications', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Multimodal Models']
---
The emergence of Vision-Language Models (VLMs) represents a significant
advancement in integrating computer vision with Large Language Models (LLMs) to
generate detailed text descriptions from visual inputs. Despite their growing
importance, the security of VLMs, particularly against backdoor attacks, is
under explored. Moreover, prior works often assume attackers have access to the
original training data, which is often unrealistic. In this paper, we address a
more practical and challenging scenario where attackers must rely solely on
Out-Of-Distribution (OOD) data. We introduce VLOOD (Backdooring Vision-Language
Models with Out-of-Distribution Data), a novel approach with two key
contributions: (1) demonstrating backdoor attacks on VLMs in complex
image-to-text tasks while minimizing degradation of the original semantics
under poisoned inputs, and (2) proposing innovative techniques for backdoor
injection without requiring any access to the original training data. Our
evaluation on image captioning and visual question answering (VQA) tasks
confirms the effectiveness of VLOOD, revealing a critical security
vulnerability in VLMs and laying the foundation for future research on securing
multimodal models against sophisticated threats.
