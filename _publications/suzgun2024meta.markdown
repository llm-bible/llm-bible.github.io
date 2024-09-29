---
layout: publication
title: Meta45;prompting Enhancing Language Models With Task45;agnostic Scaffolding
authors: Suzgun Mirac, Kalai Adam Tauman
conference: "Arxiv"
year: 2024
bibkey: suzgun2024meta
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2401.12954"}
tags: ['GPT', 'Model Architecture', 'Pretraining Methods', 'Prompting', 'RAG', 'Tools']
---
We introduce meta45;prompting an effective scaffolding technique designed to enhance the functionality of language models (LMs). This approach transforms a single LM into a multi45;faceted conductor adept at managing and integrating multiple independent LM queries. By employing high45;level instructions meta45;prompting guides the LM to break down complex tasks into smaller more manageable subtasks. These subtasks are then handled by distinct expert instances of the same LM each operating under specific tailored instructions. Central to this process is the LM itself in its role as the conductor which ensures seamless communication and effective integration of the outputs from these expert models. It additionally employs its inherent critical thinking and robust verification processes to refine and authenticate the end result. This collaborative prompting approach empowers a single LM to simultaneously act as a comprehensive orchestrator and a panel of diverse experts significantly enhancing its performance across a wide array of tasks. The zero45;shot task45;agnostic nature of meta45;prompting greatly simplifies user interaction by obviating the need for detailed task45;specific instructions. Furthermore our research demonstrates the seamless integration of external tools such as a Python interpreter into the meta45;prompting framework thereby broadening its applicability and utility. Through rigorous experimentation with GPT45;4 we establish the superiority of meta45;prompting over conventional scaffolding methods When averaged across all tasks including the Game of 24 Checkmate45;in45;One and Python Programming Puzzles meta45;prompting augmented with a Python interpreter functionality surpasses standard prompting by 17.137; expert (dynamic) prompting by 17.337; and multipersona prompting by 15.237;.
