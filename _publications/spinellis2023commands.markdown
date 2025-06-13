---
layout: publication
title: 'Commands As AI Conversations'
authors: Diomidis Spinellis
conference: "Arxiv"
year: 2023
bibkey: spinellis2023commands
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2309.06551'}
tags: ['GPT', 'Tools', 'Prompting', 'Model Architecture']
---
Developers and data scientists often struggle to write command-line inputs,
even though graphical interfaces or tools like ChatGPT can assist. The
solution? "ai-cli," an open-source system inspired by GitHub Copilot that
converts natural language prompts into executable commands for various Linux
command-line tools. By tapping into OpenAI's API, which allows interaction
through JSON HTTP requests, "ai-cli" transforms user queries into actionable
command-line instructions. However, integrating AI assistance across multiple
command-line tools, especially in open source settings, can be complex.
Historically, operating systems could mediate, but individual tool
functionality and the lack of a unified approach have made centralized
integration challenging. The "ai-cli" tool, by bridging this gap through
dynamic loading and linking with each program's Readline library API, makes
command-line interfaces smarter and more user-friendly, opening avenues for
further enhancement and cross-platform applicability.
