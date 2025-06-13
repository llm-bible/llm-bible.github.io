---
layout: publication
title: 'Expertlongbench: Benchmarking Language Models On Expert-level Long-form Generation Tasks With Structured Checklists'
authors: Jie Ruan, Inderjeet Nair, Shuyang Cao, Amy Liu, Sheza Munir, Micah Pollens-dempsey, Tiffany Chiang, Lucy Kates, Nicholas David, Sihan Chen, Ruxin Yang, Yuqian Yang, Jasmine Gump, Tessa Bialek, Vivek Sankaran, Margo Schlanger, Lu Wang
conference: "Arxiv"
year: 2025
bibkey: ruan2025benchmarking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2506.01241'}
tags: ['Reinforcement Learning', 'Applications', 'Tools']
---
This paper introduces ExpertLongBench, an expert-level benchmark containing 11 tasks from 9 domains that reflect realistic expert workflows and applications. Beyond question answering, the application-driven tasks in ExpertLongBench demand long-form outputs that can exceed 5,000 tokens and strict adherence to domain-specific requirements. Notably, each task in ExpertLongBench includes a rubric, designed or validated by domain experts, to specify task requirements and guide output evaluation. Furthermore, we propose CLEAR, an evaluation framework that supports accurate evaluation of long-form model outputs in our benchmark. To achieve fine-grained, expert-aligned evaluation, CLEAR derives checklists from both model outputs and references by extracting information corresponding to items in the task-specific rubric. Checklist items for model outputs are then compared with corresponding items for reference outputs to assess their correctness, enabling grounded evaluation. We benchmark 11 large language models (LLMs) and analyze components in CLEAR, showing that (1) existing LLMs, with the top performer achieving only a 26.8% F1 score, require significant improvement for expert-level tasks; (2) models can generate content corresponding to the required aspects, though often not accurately; and (3) accurate checklist extraction and comparison in CLEAR can be achieved by open-weight models for more scalable and low-cost usage.
