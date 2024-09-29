---
layout: publication
title: Deduction Under Perturbed Evidence&#58; Probing Student Simulation Capabilities Of Large Language Models
authors: Sonkar Shashank, Baraniuk Richard G.
conference: "Arxiv"
year: 2023
bibkey: sonkar2023deduction
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2305.14507"}
tags: ['Applications', 'Ethics And Bias', 'GPT', 'Model Architecture', 'Prompting', 'Reinforcement Learning']
---
We explore whether Large Language Models (LLMs) are capable of logical reasoning with distorted facts which we call Deduction under Perturbed Evidence (DUPE). DUPE presents a unique challenge to LLMs since they typically rely on their parameters which encode mostly accurate information to reason and make inferences. However in DUPE LLMs must reason over manipulated or falsified evidence present in their prompts which can result in false conclusions that are valid only under the manipulated evidence. Our goal with DUPE is to determine whether LLMs can arrive at these false conclusions and identify whether the dominant factor influencing the deduction process is the encoded data in the parameters or the manipulated evidence in the prompts. To evaluate the DUPE capabilities of LLMs we create a DUPEd version of the StrategyQA dataset where facts are manipulated to reverse the answer to the question. Our findings show that even the most advanced GPT models struggle to reason on manipulated facts - showcasing poor DUPE skills - with accuracy dropping by 4537; compared to the original dataset. We also investigate prompt settings inspired from student simulation models which mitigate the accuracy drop to some extent. Our findings have practical implications for understanding the performance of LLMs in real-world applications such as student simulation models that involve reasoning over inaccurate information.
