---
layout: publication
title: 'Drawing Pandas: A Benchmark For Llms In Generating Plotting Code'
authors: Timur Galimzyanov, Sergey Titov, Yaroslav Golubev, Egor Bogomolov
conference: "Arxiv"
year: 2024
bibkey: galimzyanov2024drawing
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2412.02764'}
  - {name: "Code", url: 'https://huggingface.co/datasets/JetBrains-Research/PandasPlotBench;'}
  - {name: "Code", url: 'https://github.com/JetBrains-Research/PandasPlotBench'}
tags: ['Fine-Tuning', 'Has Code', 'Tools']
---
This paper introduces the human-curated PandasPlotBench dataset, designed to
evaluate language models' effectiveness as assistants in visual data
exploration. Our benchmark focuses on generating code for visualizing tabular
data - such as a Pandas DataFrame - based on natural language instructions,
complementing current evaluation tools and expanding their scope. The dataset
includes 175 unique tasks. Our experiments assess several leading Large
Language Models (LLMs) across three visualization libraries: Matplotlib,
Seaborn, and Plotly. We show that the shortening of tasks has a minimal effect
on plotting capabilities, allowing for the user interface that accommodates
concise user input without sacrificing functionality or accuracy. Another of
our findings reveals that while LLMs perform well with popular libraries like
Matplotlib and Seaborn, challenges persist with Plotly, highlighting areas for
improvement. We hope that the modular design of our benchmark will broaden the
current studies on generating visualizations. Our dataset and benchmark code
are available online:
https://huggingface.co/datasets/JetBrains-Research/PandasPlotBench;
https://github.com/JetBrains-Research/PandasPlotBench.
