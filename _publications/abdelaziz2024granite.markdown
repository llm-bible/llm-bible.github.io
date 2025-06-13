---
layout: publication
title: 'Granite-function Calling Model: Introducing Function Calling Abilities Via Multi-task Learning Of Granular Tasks'
authors: Ibrahim Abdelaziz, Kinjal Basu, Mayank Agarwal, Sadhana Kumaravel, Matthew Stallone, Rameswar Panda, Yara Rizk, Gp Bhargav, Maxwell Crouse, Chulaka Gunasekara, Shajith Ikbal, Sachin Joshi, Hima Karanam, Vineet Kumar, Asim Munawar, Sumit Neelam, Dinesh Raghu, Udit Sharma, Adriana Meza Soria, Dheeraj Sreedhar, Praveen Venkateswaran, Merve Unuvar, David Cox, Salim Roukos, Luis Lastras, Pavan Kapanipathi
conference: "Arxiv"
year: 2024
bibkey: abdelaziz2024granite
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.00121"}
tags: ['Agentic', 'GPT', 'Tools', 'Model Architecture', 'Training Techniques']
---
Large language models (LLMs) have recently shown tremendous promise in
serving as the backbone to agentic systems, as demonstrated by their
performance in multi-faceted, challenging benchmarks like SWE-Bench and
Agent-Bench. However, to realize the true potential of LLMs as autonomous
agents, they must learn to identify, call, and interact with external tools and
application program interfaces (APIs) to complete complex tasks. These tasks
together are termed function calling. Endowing LLMs with function calling
abilities leads to a myriad of advantages, such as access to current and
domain-specific information in databases and knowledge sources, and the ability
to outsource tasks that can be reliably performed by tools, e.g., a Python
interpreter or calculator. While there has been significant progress in
function calling with LLMs, there is still a dearth of open models that perform
on par with proprietary LLMs like GPT, Claude, and Gemini. Therefore, in this
work, we introduce the GRANITE-20B-FUNCTIONCALLING model under an Apache 2.0
license. The model is trained using a multi-task training approach on seven
fundamental tasks encompassed in function calling, those being Nested Function
Calling, Function Chaining, Parallel Functions, Function Name Detection,
Parameter-Value Pair Detection, Next-Best Function, and Response Generation. We
present a comprehensive evaluation on multiple out-of-domain datasets comparing
GRANITE-20B-FUNCTIONCALLING to more than 15 other best proprietary and open
models. GRANITE-20B-FUNCTIONCALLING provides the best performance among all
open models on the Berkeley Function Calling Leaderboard and fourth overall. As
a result of the diverse tasks and datasets used for training our model, we show
that GRANITE-20B-FUNCTIONCALLING has better generalizability on multiple tasks
in seven different evaluation datasets.
