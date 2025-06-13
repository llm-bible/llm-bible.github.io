---
layout: publication
title: 'Promptpex: Automatic Test Generation For Language Model Prompts'
authors: Reshabh K Sharma, Jonathan De Halleux, Shraddha Barke, Benjamin Zorn
conference: "Arxiv"
year: 2025
bibkey: sharma2025automatic
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2503.05070"}
  - {name: "Code", url: "https://github.com/microsoft/promptpex"}
tags: ['Prompting', 'Applications', 'Has Code', 'Reinforcement Learning']
---
Large language models (LLMs) are being used in many applications and prompts
for these models are integrated into software applications as code-like
artifacts. These prompts behave much like traditional software in that they
take inputs, generate outputs, and perform some specific function. However,
prompts differ from traditional code in many ways and require new approaches to
ensure that they are robust. For example, unlike traditional software the
output of a prompt depends on the AI model that interprets it. Also, while
natural language prompts are easy to modify, the impact of updates is harder to
predict. New approaches to testing, debugging, and modifying prompts with
respect to the model running them are required.
  To address some of these issues, we developed PromptPex, an LLM-based tool to
automatically generate and evaluate unit tests for a given prompt. PromptPex
extracts input and output specifications from a prompt and uses them to
generate diverse, targeted, and valid unit tests. These tests are instrumental
in identifying regressions when a prompt is changed and also serve as a tool to
understand how prompts are interpreted by different models. We use PromptPex to
generate tests for eight benchmark prompts and evaluate the quality of the
generated tests by seeing if they can cause each of four diverse models to
produce invalid output. PromptPex consistently creates tests that result in
more invalid model outputs than a carefully constructed baseline LLM-based test
generator. Furthermore, by extracting concrete specifications from the input
prompt, PromptPex allows prompt writers to clearly understand and test specific
aspects of their prompts. The source code of PromptPex is available at
https://github.com/microsoft/promptpex.
