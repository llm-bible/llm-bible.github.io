---
layout: publication
title: 'LLM Should Think And Action As A Human'
authors: Haun Leung, Zinan Wang
conference: "Arxiv"
year: 2025
bibkey: leung2025llm
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2502.13475"}
tags: ['Agentic', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Prompting']
---
It is popular lately to train large language models to be used as chat
assistants, but in the conversation between the user and the chat assistant,
there are prompts, require multi-turns between the chat assistant and the user.
However, there are a number of issues with the multi-turns conversation: The
response of the chat assistant is prone to errors and can't help users achieve
their goals, and as the number of conversation turns increases, the probability
of errors will also increase; It is difficult for chat assistant to generate
responses with different processes based on actual needs for the same prompt;
Chat assistant require the use of tools, but the current approach is not
elegant and efficient, and the number of tool calls is limited. The main reason
for these issues is that large language models don't have the thinking ability
as a human, lack the reasoning ability and planning ability, and lack the
ability to execute plans. To solve these issues, we propose a thinking method
based on a built-in chain of thought: In the multi-turns conversation, for each
user prompt, the large language model thinks based on elements such as chat
history, thinking context, action calls, memory and knowledge, makes detailed
reasoning and planning, and actions according to the plan. We also explored how
the large language model enhances thinking ability through this thinking
method: Collect training datasets according to the thinking method and fine
tune the large language model through supervised learning; Train a consistency
reward model and use it as a reward function to fine tune the large language
model using reinforcement learning, and the reinforced large language model
outputs according to this way of thinking. Our experimental results show that
the reasoning ability and planning ability of the large language model are
enhanced, and the issues in the multi-turns conversation are solved.
