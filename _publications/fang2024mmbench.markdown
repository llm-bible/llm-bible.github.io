---
layout: publication
title: 'Mmbench-video: A Long-form Multi-shot Benchmark For Holistic Video Understanding'
authors: Xinyu Fang, Kangrui Mao, Haodong Duan, Xiangyu Zhao, Yining Li, Dahua Lin, Kai Chen
conference: "Arxiv"
year: 2024
bibkey: fang2024mmbench
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2406.14515'}
  - {name: "Code", url: 'https://github.com/open-compass/VLMEvalKit'}
tags: ['Has Code', 'Security', 'Model Architecture', 'Applications', 'GPT', 'Multimodal Models', 'Reinforcement Learning']
---
The advent of large vision-language models (LVLMs) has spurred research into
their applications in multi-modal contexts, particularly in video
understanding. Traditional VideoQA benchmarks, despite providing quantitative
metrics, often fail to encompass the full spectrum of video content and
inadequately assess models' temporal comprehension. To address these
limitations, we introduce MMBench-Video, a quantitative benchmark designed to
rigorously evaluate LVLMs' proficiency in video understanding. MMBench-Video
incorporates lengthy videos from YouTube and employs free-form questions,
mirroring practical use cases. The benchmark is meticulously crafted to probe
the models' temporal reasoning skills, with all questions human-annotated
according to a carefully constructed ability taxonomy. We employ GPT-4 for
automated assessment, demonstrating superior accuracy and robustness over
earlier LLM-based evaluations. Utilizing MMBench-Video, we have conducted
comprehensive evaluations that include both proprietary and open-source LVLMs
for images and videos. MMBench-Video stands as a valuable resource for the
research community, facilitating improved evaluation of LVLMs and catalyzing
progress in the field of video understanding. The evalutation code of
MMBench-Video will be integrated into VLMEvalKit:
https://github.com/open-compass/VLMEvalKit.
