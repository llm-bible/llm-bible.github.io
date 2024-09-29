---
layout: publication
title: Can Large Language Models Explore In45;context
authors: Krishnamurthy Akshay, Harris Keegan, Foster Dylan J., Zhang Cyril, Slivkins Aleksandrs
conference: "Arxiv"
year: 2024
bibkey: krishnamurthy2024can
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2403.15371"}
tags: ['Agentic', 'Applications', 'Fine Tuning', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
We investigate the extent to which contemporary Large Language Models (LLMs) can engage in exploration a core capability in reinforcement learning and decision making. We focus on native performance of existing LLMs without training interventions. We deploy LLMs as agents in simple multi45;armed bandit environments specifying the environment description and interaction history entirely in45;context i.e. within the LLM prompt. We experiment with GPT45;3.5 GPT45;4 and Llama2 using a variety of prompt designs and find that the models do not robustly engage in exploration without substantial interventions i) Across all of our experiments only one configuration resulted in satisfactory exploratory behavior GPT45;4 with chain45;of45;thought reasoning and an externally summarized interaction history presented as sufficient statistics; ii) All other configurations did not result in robust exploratory behavior including those with chain45;of45;thought reasoning but unsummarized history. Although these findings can be interpreted positively they suggest that external summarization 45;45; which may not be possible in more complex settings 45;45; is important for obtaining desirable behavior from LLM agents. We conclude that non45;trivial algorithmic interventions such as fine45;tuning or dataset curation may be required to empower LLM45;based decision making agents in complex settings.
