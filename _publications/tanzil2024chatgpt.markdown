---
layout: publication
title: 'Chatgpt Incorrectness Detection In Software Reviews'
authors: Minaoar Hossain Tanzil, Junaed Younus Khan, Gias Uddin
conference: "IEEE/ACM 46th International Conference on Software Engineering (ICSE 2024)"
year: 2024
bibkey: tanzil2024chatgpt
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.16347"}
tags: ['Model Architecture', 'Survey Paper', 'Tools', 'Reinforcement Learning', 'GPT', 'Prompting']
---
We conducted a survey of 135 software engineering (SE) practitioners to
understand how they use Generative AI-based chatbots like ChatGPT for SE tasks.
We find that they want to use ChatGPT for SE tasks like software library
selection but often worry about the truthfulness of ChatGPT responses. We
developed a suite of techniques and a tool called CID (ChatGPT Incorrectness
Detector) to automatically test and detect the incorrectness in ChatGPT
responses. CID is based on the iterative prompting to ChatGPT by asking it
contextually similar but textually divergent questions (using an approach that
utilizes metamorphic relationships in texts). The underlying principle in CID
is that for a given question, a response that is different from other responses
(across multiple incarnations of the question) is likely an incorrect response.
In a benchmark study of library selection, we show that CID can detect
incorrect responses from ChatGPT with an F1-score of 0.74 - 0.75.
