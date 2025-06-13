---
layout: publication
title: 'Llms As Method Actors: A Model For Prompt Engineering And Architecture'
authors: Colin Doyle
conference: "Arxiv"
year: 2024
bibkey: doyle2024llms
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2411.05778"}
tags: ['Tools', 'GPT', 'Prompting', 'Model Architecture']
---
We introduce "Method Actors" as a mental model for guiding LLM prompt
engineering and prompt architecture. Under this mental model, LLMs should be
thought of as actors; prompts as scripts and cues; and LLM responses as
performances. We apply this mental model to the task of improving LLM
performance at playing Connections, a New York Times word puzzle game that
prior research identified as a challenging benchmark for evaluating LLM
reasoning. Our experiments with GPT-4o show that a "Method Actors" approach can
significantly improve LLM performance over both a vanilla and "Chain of
Thoughts" approach. A vanilla approach solves 27% of Connections puzzles in our
dataset and a "Chain of Thoughts" approach solves 41% of puzzles, whereas our
strongest "Method Actor" approach solves 86% of puzzles. We also test OpenAI's
newest model designed specifically for complex reasoning tasks, o1-preview.
When asked to solve a puzzle all at once, o1-preview solves 79% of Connections
puzzles in our dataset, and when allowed to build puzzle solutions one guess at
a time over multiple API calls, o1-preview solves 100% of the puzzles.
Incorporating a "Method Actor" prompt architecture increases the percentage of
puzzles that o1-preview solves perfectly from 76% to 87%.
