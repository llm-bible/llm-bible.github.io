---
layout: publication
title: 'Task-oriented Prompt Enhancement Via Script Generation'
authors: Chung-yu Wang, Alireza Daghighfarsoodeh, Hung Viet Pham
conference: "Arxiv"
year: 2024
bibkey: wang2024task
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.16418"}
tags: ['Model Architecture', 'Few-Shot', 'RAG', 'GPT', 'Prompting', 'Applications']
---
Large Language Models (LLMs) have demonstrated remarkable abilities across
various tasks, leveraging advanced reasoning. Yet, they struggle with
task-oriented prompts due to a lack of specific prior knowledge of the task
answers. The current state-of-the-art approach, PAL, utilizes code generation
to address this issue. However, PAL depends on manually crafted prompt
templates and examples while still producing inaccurate results. In this work,
we present TITAN-a novel strategy designed to enhance LLMs' performance on
task-oriented prompts. TITAN achieves this by generating scripts using a
universal approach and zero-shot learning. Unlike existing methods, TITAN
eliminates the need for detailed task-specific instructions and extensive
manual efforts. TITAN enhances LLMs' performance on various tasks by utilizing
their analytical and code-generation capabilities in a streamlined process.
TITAN employs two key techniques: (1) step-back prompting to extract the task's
input specifications and (2) chain-of-thought prompting to identify required
procedural steps. This information is used to improve the LLMs' code-generation
process. TITAN further refines the generated script through post-processing and
the script is executed to retrieve the final answer. Our comprehensive
evaluation demonstrates TITAN's effectiveness in a diverse set of tasks. On
average, TITAN outperforms the state-of-the-art zero-shot approach by 7.6% and
3.9% when paired with GPT-3.5 and GPT-4. Overall, without human annotation,
TITAN achieves state-of-the-art performance in 8 out of 11 cases while only
marginally losing to few-shot approaches (which needed human intervention) on
three occasions by small margins. This work represents a significant
advancement in addressing task-oriented prompts, offering a novel solution for
effectively utilizing LLMs in everyday life tasks.
