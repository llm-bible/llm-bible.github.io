---
layout: publication
title: Ask Me Anything A Simple Strategy For Prompting Language Models
authors: Simran Arora, Avanika Narayan, Mayee F. Chen, Laurel Orr, Neel Guha, Kush Bhatia, Ines Chami, Frederic Sala, Christopher Ré
conference: "Arxiv"
year: 2022
bibkey: arora2022ask
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/http://arxiv.org/abs/2210.02441v3"}
  - {name: "Code", url: "https://github.com/HazyResearch/ama&#95;prompting"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'RAG', 'Training Techniques']
---
Large language models (LLMs) transfer well to new tasks out45;of45;the45;box simply given a natural language prompt that demonstrates how to perform the task and no additional training. Prompting is a brittle process wherein small modifications to the prompt can cause large variations in the model predictions and therefore significant effort is dedicated towards designing a painstakingly perfect prompt for a task. To mitigate the high degree of effort involved in prompt45;design we instead ask whether producing multiple effective yet imperfect prompts and aggregating them can lead to a high quality prompting strategy. Our observations motivate our proposed prompting method ASK ME ANYTHING (AMA). We first develop an understanding of the effective prompt formats finding that question45;answering (QA) prompts which encourage open45;ended generation (Who went to the park) tend to outperform those that restrict the model outputs (John went to the park. Output True or False.). Our approach recursively uses the LLM itself to transform task inputs to the effective QA format. We apply the collected prompts to obtain several noisy votes for the inputs true label. We find that the prompts can have very different accuracies and complex dependencies and thus propose to use weak supervision a procedure for combining the noisy predictions to produce the final predictions for the inputs. We evaluate AMA across open45;source model families (e.g. EleutherAI BLOOM OPT and T0) and model sizes (125M45;175B parameters) demonstrating an average performance lift of 10.237; over the few45;shot baseline. This simple strategy enables the open45;source GPT45;J45;6B model to match and exceed the performance of few45;shot GPT345;175B on 15 of 20 popular benchmarks. Averaged across these tasks the GPT45;J45;6B model outperforms few45;shot GPT345;175B. We release our code here https://github.com/HazyResearch/ama&#95;prompting
