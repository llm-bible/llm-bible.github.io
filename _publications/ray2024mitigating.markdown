---
layout: publication
title: 'Mitigating Exaggerated Safety In Large Language Models'
authors: Ruchira Ray, Ruchi Bhalani
conference: "Arxiv"
year: 2024
bibkey: ray2024mitigating
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2405.05418"}
tags: ['Responsible AI', 'Few-Shot', 'Prompting', 'In-Context Learning']
---
As the popularity of Large Language Models (LLMs) grow, combining model
safety with utility becomes increasingly important. The challenge is making
sure that LLMs can recognize and decline dangerous prompts without sacrificing
their ability to be helpful. The problem of "exaggerated safety" demonstrates
how difficult this can be. To reduce excessive safety behaviours -- which was
discovered to be 26.1% of safe prompts being misclassified as dangerous and
refused -- we use a combination of XSTest dataset prompts as well as
interactive, contextual, and few-shot prompting to examine the decision bounds
of LLMs such as Llama2, Gemma Command R+, and Phi-3. We find that few-shot
prompting works best for Llama2, interactive prompting works best Gemma, and
contextual prompting works best for Command R+ and Phi-3. Using a combination
of these prompting strategies, we are able to mitigate exaggerated safety
behaviors by an overall 92.9% across all LLMs. Our work presents a multiple
prompting strategies to jailbreak LLMs' decision-making processes, allowing
them to navigate the tight line between refusing unsafe prompts and remaining
helpful.
