---
layout: publication
title: Decomposed Prompting A Modular Approach For Solving Complex Tasks
authors: Khot Tushar, Trivedi Harsh, Finlayson Matthew, Fu Yao, Richardson Kyle, Clark Peter, Sabharwal Ashish
conference: "Arxiv"
year: 2022
bibkey: khot2022decomposed
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2210.02406"}
  - {name: "Code", url: "https://github.com/allenai/DecomP"}
tags: ['Applications', 'GPT', 'Has Code', 'Model Architecture', 'Prompting', 'Tools']
---
Few45;shot prompting is a surprisingly powerful way to use Large Language Models (LLMs) to solve various tasks. However this approach struggles as the task complexity increases or when the individual reasoning steps of the task themselves are hard to learn especially when embedded in more complex tasks. To address this we propose Decomposed Prompting a new approach to solve complex tasks by decomposing them (via prompting) into simpler sub45;tasks that can be delegated to a library of prompting45;based LLMs dedicated to these sub45;tasks. This modular structure allows each prompt to be optimized for its specific sub45;task further decomposed if necessary and even easily replaced with more effective prompts trained models or symbolic functions if desired. We show that the flexibility and modularity of Decomposed Prompting allows it to outperform prior work on few45;shot prompting using GPT3. On symbolic reasoning tasks we can further decompose sub45;tasks that are hard for LLMs into even simpler solvable sub45;tasks. When the complexity comes from the input length we can recursively decompose the task into the same task but with smaller inputs. We also evaluate our approach on textual multi45;step reasoning tasks on long45;context multi45;hop QA task we can more effectively teach the sub45;tasks via our separate sub45;tasks prompts; and on open45;domain multi45;hop QA we can incorporate a symbolic information retrieval within our decomposition framework leading to improved performance on both tasks. Datasets Code and Prompts available at https://github.com/allenai/DecomP.
