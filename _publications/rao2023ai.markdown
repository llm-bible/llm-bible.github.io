---
layout: publication
title: 'AI For Low-code For AI'
authors: Nikitha Rao, Jason Tsay, Kiran Kate, Vincent J. Hellendoorn, Martin Hirzel
conference: "Arxiv"
year: 2023
bibkey: rao2023ai
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.20015"}
tags: ['Model Architecture', 'Tools', 'Reinforcement Learning', 'RAG', 'GPT']
---
Low-code programming allows citizen developers to create programs with
minimal coding effort, typically via visual (e.g. drag-and-drop) interfaces. In
parallel, recent AI-powered tools such as Copilot and ChatGPT generate programs
from natural language instructions. We argue that these modalities are
complementary: tools like ChatGPT greatly reduce the need to memorize large
APIs but still require their users to read (and modify) programs, whereas
visual tools abstract away most or all programming but struggle to provide easy
access to large APIs. At their intersection, we propose LowCoder, the first
low-code tool for developing AI pipelines that supports both a visual
programming interface (LowCoder_VP) and an AI-powered natural language
interface (LowCoder_NL). We leverage this tool to provide some of the first
insights into whether and how these two modalities help programmers by
conducting a user study. We task 20 developers with varying levels of AI
expertise with implementing four ML pipelines using LowCoder, replacing the
LowCoder_NL component with a simple keyword search in half the tasks. Overall,
we find that LowCoder is especially useful for (i) Discoverability: using
LowCoder_NL, participants discovered new operators in 75% of the tasks,
compared to just 32.5% and 27.5% using web search or scrolling through options
respectively in the keyword-search condition, and (ii) Iterative Composition:
82.5% of tasks were successfully completed and many initial pipelines were
further successfully improved. Qualitative analysis shows that AI helps users
discover how to implement constructs when they know what to do, but still fails
to support novices when they lack clarity on what they want to accomplish.
Overall, our work highlights the benefits of combining the power of AI with
low-code programming.
