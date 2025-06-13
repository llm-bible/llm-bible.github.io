---
layout: publication
title: 'BAP V2: An Enhanced Task Framework For Instruction Following In Minecraft Dialogues'
authors: Prashant Jayannavar, Liliang Ren, Marisa Hudspeth, Charlotte Lambert, Ariel Cordes, Elizabeth Kaplan, Anjali Narayan-chen, Julia Hockenmaier
conference: "Arxiv"
year: 2025
bibkey: jayannavar2025bap
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2501.10836"}
tags: ['Agentic', 'Security', 'Model Architecture', 'Training Techniques', 'Multimodal Models', 'Tools', 'Reinforcement Learning', 'Pretraining Methods', 'Fine-Tuning', 'Transformer']
---
Interactive agents capable of understanding and executing instructions in the
physical world have long been a central goal in AI research. The Minecraft
Collaborative Building Task (MCBT) provides one such setting to work towards
this goal (Narayan-Chen, Jayannavar, and Hockenmaier 2019). It is a two-player
game in which an Architect (A) instructs a Builder (B) to construct a target
structure in a simulated Blocks World Environment. We focus on the challenging
Builder Action Prediction (BAP) subtask of predicting correct action sequences
in a given multimodal game context with limited training data (Jayannavar,
Narayan-Chen, and Hockenmaier 2020). We take a closer look at evaluation and
data for the BAP task, discovering key challenges and making significant
improvements on both fronts to propose BAP v2, an upgraded version of the task.
This will allow future work to make more efficient and meaningful progress on
it. It comprises of: (1) an enhanced evaluation benchmark that includes a
cleaner test set and fairer, more insightful metrics, and (2) additional
synthetic training data generated from novel Minecraft dialogue and target
structure simulators emulating the MCBT. We show that the synthetic data can be
used to train more performant and robust neural models even with relatively
simple training methods. Looking ahead, such data could also be crucial for
training more sophisticated, data-hungry deep transformer models and
training/fine-tuning increasingly large LLMs. Although modeling is not the
primary focus of this work, we also illustrate the impact of our data and
training methodologies on a simple LLM- and transformer-based model, thus
validating the robustness of our approach, and setting the stage for more
advanced architectures and LLMs going forward.
