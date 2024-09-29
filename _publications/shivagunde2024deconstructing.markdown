---
layout: publication
title: Deconstructing In-context Learning&#58; Understanding Prompts Via Corruption
authors: Shivagunde Namrata, Lialin Vladislav, Muckatira Sherin, Rumshisky Anna
conference: "Arxiv"
year: 2024
bibkey: shivagunde2024deconstructing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02054"}
tags: ['Few Shot', 'GPT', 'In Context Learning', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
The ability of large language models (LLMs) to learn in context based on the provided prompt has led to an explosive growth in their use culminating in the proliferation of AI assistants such as ChatGPT Claude and Bard. These AI assistants are known to be robust to minor prompt modifications mostly due to alignment techniques that use human feedback. In contrast the underlying pre-trained LLMs they use as a backbone are known to be brittle in this respect. Building high-quality backbone models remains a core challenge and a common approach to assessing their quality is to conduct few-shot evaluation. Such evaluation is notorious for being highly sensitive to minor prompt modifications as well as the choice of specific in-context examples. Prior work has examined how modifying different elements of the prompt can affect model performance. However these earlier studies tended to concentrate on a limited number of specific prompt attributes and often produced contradictory results. Additionally previous research either focused on models with fewer than 15 billion parameters or exclusively examined black-box models like GPT-3 or PaLM making replication challenging. In the present study we decompose the entire prompt into four components task description demonstration inputs labels and inline instructions provided for each demonstration. We investigate the effects of structural and semantic corruptions of these elements on model performance. We study models ranging from 1.5B to 70B in size using ten datasets covering classification and generation tasks. We find that repeating text within the prompt boosts model performance and bigger models ((geq)30B) are more sensitive to the semantics of the prompt. Finally we observe that adding task and inline instructions to the demonstrations enhances model performance even when the instructions are semantically corrupted.
