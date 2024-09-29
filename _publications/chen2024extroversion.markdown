---
layout: publication
title: Extroversion Or Introversion Controlling The Personality Of Your Large Language Models
authors: Chen Yanquan, Wu Zhen, Guo Junjie, Huang Shujian, Dai Xinyu
conference: "Arxiv"
year: 2024
bibkey: chen2024extroversion
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.04583"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'Language Modeling', 'Prompting', 'Reinforcement Learning', 'Security', 'Training Techniques']
---
Large language models (LLMs) exhibit robust capabilities in text generation and comprehension mimicking human behavior and exhibiting synthetic personalities. However some LLMs have displayed offensive personality propagating toxic discourse. Existing literature neglects the origin and evolution of LLM personalities as well as the effective personality control. To fill these gaps our study embarked on a comprehensive investigation into LLM personality control. We investigated several typical methods to influence LLMs including three training methods Continual Pre45;training Supervised Fine45;Tuning (SFT) and Reinforcement Learning from Human Feedback (RLHF) along with inference phase considerations (prompts). Our investigation revealed a hierarchy of effectiveness in control Prompt SFT RLHF Continual Pre45;train. Notably SFT exhibits a higher control success rate compared to prompt induction. While prompts prove highly effective we found that prompt45;induced personalities are less robust than those trained making them more prone to showing conflicting personalities under reverse personality prompt induction. Besides harnessing the strengths of both SFT and prompt we proposed underline123;text123;P125;125;rompt underline123;text123;I125;125;nduction post underline123;text123;S125;125;upervised underline123;text123;F125;125;ine45;tuning (PISF) which emerges as the most effective and robust strategy for controlling LLMs personality displaying high efficacy high success rates and high robustness. Even under reverse personality prompt induction LLMs controlled by PISF still exhibit stable and robust personalities.
