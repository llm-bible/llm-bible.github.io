---
layout: publication
title: 'Intriguing Properties Of Large Language And Vision Models'
authors: Young-jun Lee, Byungsoo Ko, Han-gyu Kim, Yechan Hwang, Ho-jin Choi
conference: "Arxiv"
year: 2024
bibkey: lee2024intriguing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.04751"}
tags: ['Security', 'Model Architecture', 'Attention Mechanism', 'Multimodal Models']
---
Recently, large language and vision models (LLVMs) have received significant
attention and development efforts due to their remarkable generalization
performance across a wide range of tasks requiring perception and cognitive
abilities. A key factor behind their success is their simple architecture,
which consists of a vision encoder, a projector, and a large language model
(LLM). Despite their achievements in advanced reasoning tasks, their
performance on fundamental perception-related tasks (e.g., MMVP) remains
surprisingly low. This discrepancy raises the question of how LLVMs truly
perceive images and exploit the advantages of the vision encoder. To address
this, we systematically investigate this question regarding several aspects:
permutation invariance, robustness, math reasoning, alignment preserving and
importance, by evaluating the most common LLVM's families (i.e., LLaVA) across
10 evaluation benchmarks. Our extensive experiments reveal several intriguing
properties of current LLVMs: (1) they internally process the image in a global
manner, even when the order of visual patch sequences is randomly permuted; (2)
they are sometimes able to solve math problems without fully perceiving
detailed numerical information; (3) the cross-modal alignment is overfitted to
complex reasoning tasks, thereby, causing them to lose some of the original
perceptual capabilities of their vision encoder; (4) the representation space
in the lower layers (<25%) plays a crucial role in determining performance and
enhancing visual understanding. Lastly, based on the above observations, we
suggest potential future directions for building better LLVMs and constructing
more challenging evaluation benchmarks.
