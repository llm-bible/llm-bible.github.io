---
layout: publication
title: 'Incremental Learning Of Humanoid Robot Behavior From Natural Interaction And Large Language Models'
authors: Bärmann Leonard, Kartmann Rainer, Peller-konrad Fabian, Niehues Jan, Waibel Alex, Asfour Tamim
conference: "Arxiv"
year: 2023
bibkey: bärmann2023incremental
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2309.04316"}
tags: ['Model Architecture', 'Prompting', 'Reinforcement Learning']
---
Natural-language dialog is key for intuitive human-robot interaction. It can
be used not only to express humans' intents, but also to communicate
instructions for improvement if a robot does not understand a command
correctly. Of great importance is to endow robots with the ability to learn
from such interaction experience in an incremental way to allow them to improve
their behaviors or avoid mistakes in the future. In this paper, we propose a
system to achieve incremental learning of complex behavior from natural
interaction, and demonstrate its implementation on a humanoid robot. Building
on recent advances, we present a system that deploys Large Language Models
(LLMs) for high-level orchestration of the robot's behavior, based on the idea
of enabling the LLM to generate Python statements in an interactive console to
invoke both robot perception and action. The interaction loop is closed by
feeding back human instructions, environment observations, and execution
results to the LLM, thus informing the generation of the next statement.
Specifically, we introduce incremental prompt learning, which enables the
system to interactively learn from its mistakes. For that purpose, the LLM can
call another LLM responsible for code-level improvements of the current
interaction based on human feedback. The improved interaction is then saved in
the robot's memory, and thus retrieved on similar requests. We integrate the
system in the robot cognitive architecture of the humanoid robot ARMAR-6 and
evaluate our methods both quantitatively (in simulation) and qualitatively (in
simulation and real-world) by demonstrating generalized incrementally-learned
knowledge.
