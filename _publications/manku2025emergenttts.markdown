---
layout: publication
title: 'Emergenttts-eval: Evaluating TTS Models On Complex Prosodic, Expressiveness, And Linguistic Challenges Using Model-as-a-judge'
authors: Ruskin Raj Manku, Yuzhi Tang, Xingjian Shi, Mu Li, Alex Smola
conference: "Arxiv"
year: 2025
bibkey: manku2025emergenttts
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.23009'}
  - {name: "Code", url: 'https://github.com/boson-ai/EmergentTTS-Eval-public}{code'}
  - {name: "Code", url: 'https://huggingface.co/datasets/bosonai/EmergentTTS-Eval}{dataset'}
tags: ['Reinforcement Learning', 'Prompting', 'Has Code', 'Tools']
---
Text-to-Speech (TTS) benchmarks often fail to capture how well models handle nuanced and semantically complex text. Building on \\(\textit\{EmergentTTS\}\\), we introduce \\(\textit\{EmergentTTS-Eval\}\\), a comprehensive benchmark covering six challenging TTS scenarios: emotions, paralinguistics, foreign words, syntactic complexity, complex pronunciation (e.g. URLs, formulas), and questions. Crucially, our framework automates both test-case generation and evaluation, making the benchmark easily extensible. Starting from a small set of human-written seed prompts, we iteratively extend them using LLMs to target specific structural, phonetic and prosodic challenges, resulting in 1,645 diverse test cases. Moreover, we employ a model-as-a-judge approach, using a Large Audio Language Model (LALM) to assess the speech across multiple dimensions such as expressed emotion, prosodic, intonational, and pronunciation accuracy. We evaluate state-of-the-art open-source and proprietary TTS systems, such as 11Labs, Deepgram, and OpenAI's 4o-mini-TTS, on EmergentTTS-Eval, demonstrating its ability to reveal fine-grained performance differences. Results show that the model-as-a-judge approach offers robust TTS assessment and a high correlation with human preferences. We open source the evaluation \\(\href\{https://github.com/boson-ai/EmergentTTS-Eval-public\}\{code\}\\) and the \\(\href\{https://huggingface.co/datasets/bosonai/EmergentTTS-Eval\}\{dataset\}\\).
