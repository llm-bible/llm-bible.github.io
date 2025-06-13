---
layout: publication
title: 'SEPS: A Separability Measure For Robust Unlearning In Llms'
authors: Wonje Jeung, Sangyeon Yoon, Albert No
conference: "Arxiv"
year: 2025
bibkey: jeung2025separability
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2505.14832"}
tags: ['Tools', 'Reinforcement Learning', 'Security', 'Training Techniques', 'Prompting']
---
Machine unlearning aims to selectively remove targeted knowledge from Large Language Models (LLMs), ensuring they forget specified content while retaining essential information. Existing unlearning metrics assess whether a model correctly answers retain queries and rejects forget queries, but they fail to capture real-world scenarios where forget queries rarely appear in isolation. In fact, forget and retain queries often coexist within the same prompt, making mixed-query evaluation crucial.
  We introduce SEPS, an evaluation framework that explicitly measures a model's ability to both forget and retain information within a single prompt. Through extensive experiments across three benchmarks, we identify two key failure modes in existing unlearning methods: (1) untargeted unlearning indiscriminately erases both forget and retain content once a forget query appears, and (2) targeted unlearning overfits to single-query scenarios, leading to catastrophic failures when handling multiple queries. To address these issues, we propose Mixed Prompt (MP) unlearning, a strategy that integrates both forget and retain queries into a unified training objective. Our approach significantly improves unlearning effectiveness, demonstrating robustness even in complex settings with up to eight mixed forget and retain queries in a single prompt.
