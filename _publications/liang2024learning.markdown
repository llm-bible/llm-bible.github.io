---
layout: publication
title: 'Learning To Learn Faster From Human Feedback With Language Model Predictive Control'
authors: Jacky Liang, Fei Xia, Wenhao Yu, Andy Zeng, Montserrat Gonzalez Arenas, Maria Attarian, Maria Bauza, Matthew Bennice, Alex Bewley, Adil Dostmohamed, Chuyuan Kelly Fu, Nimrod Gileadi, Marissa Giustina, Keerthana Gopalakrishnan, Leonard Hasenclever, Jan Humplik, Jasmine Hsu, Nikhil Joshi, Ben Jyenis, Chase Kew, Sean Kirmani, Tsang-wei Edward Lee, Kuang-huei Lee, Assaf Hurwitz Michaely, Joss Moore, Ken Oslund, Dushyant Rao, Allen Ren, Baruch Tabanpour, Quan Vuong, Ayzaan Wahid, Ted Xiao, Ying Xu, Vincent Zhuang, Peng Xu, Erik Frey, Ken Caluwaerts, Tingnan Zhang, Brian Ichter, Jonathan Tompson, Leila Takayama, Vincent Vanhoucke, Izhak Shafran, Maja Mataric, Dorsa Sadigh, Nicolas Heess, Kanishka Rao, Nik Stewart, Jie Tan, Carolina Parada
conference: "Arxiv"
year: 2024
bibkey: liang2024learning
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.11450"}
  - {name: "Code", url: "https://robot-teaching.github.io/"}
tags: ['Fine-Tuning', 'Tools', 'RAG', 'Training Techniques', 'Has Code', 'Pretraining Methods', 'Prompting', 'In-Context Learning']
---
Large language models (LLMs) have been shown to exhibit a wide range of
capabilities, such as writing robot code from language commands -- enabling
non-experts to direct robot behaviors, modify them based on feedback, or
compose them to perform new tasks. However, these capabilities (driven by
in-context learning) are limited to short-term interactions, where users'
feedback remains relevant for only as long as it fits within the context size
of the LLM, and can be forgotten over longer interactions. In this work, we
investigate fine-tuning the robot code-writing LLMs, to remember their
in-context interactions and improve their teachability i.e., how efficiently
they adapt to human inputs (measured by average number of corrections before
the user considers the task successful). Our key observation is that when
human-robot interactions are viewed as a partially observable Markov decision
process (in which human language inputs are observations, and robot code
outputs are actions), then training an LLM to complete previous interactions is
training a transition dynamics model -- that can be combined with classic
robotics techniques such as model predictive control (MPC) to discover shorter
paths to success. This gives rise to Language Model Predictive Control (LMPC),
a framework that fine-tunes PaLM 2 to improve its teachability on 78 tasks
across 5 robot embodiments -- improving non-expert teaching success rates of
unseen tasks by 26.9% while reducing the average number of human corrections
from 2.4 to 1.9. Experiments show that LMPC also produces strong meta-learners,
improving the success rate of in-context learning new tasks on unseen robot
embodiments and APIs by 31.5%. See videos, code, and demos at:
https://robot-teaching.github.io/.
