---
layout: publication
title: 'Directorllm For Human-centric Video Generation'
authors: Kunpeng Song, Tingbo Hou, Zecheng He, Haoyu Ma, Jialiang Wang, Animesh Sinha, Sam Tsai, Yaqiao Luo, Xiaoliang Dai, Li Chen, Xide Xia, Peizhao Zhang, Peter Vajda, Ahmed Elgammal, Felix Juefei-xu
conference: "Arxiv"
year: 2024
bibkey: song2024directorllm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2412.14484"}
tags: ['Prompting', 'Tools', 'Reinforcement Learning']
---
In this paper, we introduce DirectorLLM, a novel video generation model that
employs a large language model (LLM) to orchestrate human poses within videos.
As foundational text-to-video models rapidly evolve, the demand for
high-quality human motion and interaction grows. To address this need and
enhance the authenticity of human motions, we extend the LLM from a text
generator to a video director and human motion simulator. Utilizing open-source
resources from Llama 3, we train the DirectorLLM to generate detailed
instructional signals, such as human poses, to guide video generation. This
approach offloads the simulation of human motion from the video generator to
the LLM, effectively creating informative outlines for human-centric scenes.
These signals are used as conditions by the video renderer, facilitating more
realistic and prompt-following video generation. As an independent LLM module,
it can be applied to different video renderers, including UNet and DiT, with
minimal effort. Experiments on automatic evaluation benchmarks and human
evaluations show that our model outperforms existing ones in generating videos
with higher human motion fidelity, improved prompt faithfulness, and enhanced
rendered subject naturalness.
