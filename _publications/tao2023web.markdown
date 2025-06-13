---
layout: publication
title: 'Webwise: Web Interface Control And Sequential Exploration With Large Language Models'
authors: Heyi Tao, Sethuraman V T, Michal Shlapentokh-rothman, Derek Hoiem
conference: "Arxiv"
year: 2023
bibkey: tao2023web
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2310.16042"}
tags: ['Fine-Tuning', 'Agentic', 'Reinforcement Learning', 'Prompting', 'In-Context Learning']
---
The paper investigates using a Large Language Model (LLM) to automatically
perform web software tasks using click, scroll, and text input operations.
Previous approaches, such as reinforcement learning (RL) or imitation learning,
are inefficient to train and task-specific. Our method uses filtered Document
Object Model (DOM) elements as observations and performs tasks step-by-step,
sequentially generating small programs based on the current observations. We
use in-context learning, either benefiting from a single manually provided
example, or an automatically generated example based on a successful zero-shot
trial. We evaluate the proposed method on the MiniWob++ benchmark. With only
one in-context example, our WebWISE method achieves similar or better
performance than other methods that require many demonstrations or trials.
