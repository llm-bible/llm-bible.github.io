---
layout: publication
title: 'Tur[k]ingbench: A Challenge Benchmark For Web Agents'
authors: Xu Kevin, Kordi Yeganeh, Nayak Tanay, Asija Ado, Wang Yizhong, Sanders Kate, Byerly Adam, Zhang Jingyu, Van Durme Benjamin, Khashabi Daniel
conference: "Arxiv"
year: 2024
bibkey: xu2024challenge
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.11905"}
tags: ['Agentic', 'GPT', 'Model Architecture', 'Multimodal Models', 'Reinforcement Learning', 'Tools']
---
Can advanced multi-modal models effectively tackle complex web-based tasks? Such tasks are often found on crowdsourcing platforms, where crowdworkers engage in challenging micro-tasks within web-based environments. Building on this idea, we present TurkingBench, a benchmark consisting of tasks presented as web pages with textual instructions and multi-modal contexts. Unlike previous approaches that rely on artificially synthesized web pages, our benchmark uses natural HTML pages originally designed for crowdsourcing workers to perform various annotation tasks. Each task's HTML instructions are instantiated with different values derived from crowdsourcing tasks, creating diverse instances. This benchmark includes 32.2K instances spread across 158 tasks. To support the evaluation of TurkingBench, we have developed a framework that links chatbot responses to actions on web pages (e.g., modifying a text box, selecting a radio button). We assess the performance of cutting-edge private and open-source models, including language-only and vision-language models (such as GPT4 and InternVL), on this benchmark. Our results show that while these models outperform random chance, there is still significant room for improvement. We hope that this benchmark will drive progress in the evaluation and development of web-based agents.
