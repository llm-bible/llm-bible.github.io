---
layout: publication
title: 'Tutorgym: A Testbed For Evaluating AI Agents As Tutors And Students'
authors: Daniel Weitekamp, Momin N. Siddiqui, Christopher J. Maclellan
conference: "Arxiv"
year: 2025
bibkey: weitekamp2025testbed
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2505.01563'}
tags: ['Agentic', 'Agent', 'Training Techniques', 'Applications', 'Tools', 'Prompting', 'Reinforcement Learning', 'In-Context Learning']
---
Recent improvements in large language model (LLM) performance on academic
benchmarks, such as MATH and GSM8K, have emboldened their use as standalone
tutors and as simulations of human learning. However, these new applications
require more than evaluations of final solution generation. We introduce
TutorGym to evaluate these applications more directly. TutorGym is a standard
interface for testing artificial intelligence (AI) agents within existing
intelligent tutoring systems (ITS) that have been tested and refined in
classroom studies, including Cognitive Tutors (CTAT), Apprentice Tutors, and
OATutors. TutorGym is more than a simple problem-solution benchmark, it
situates AI agents within the interactive interfaces of existing ITSs. At each
step of problem-solving, AI agents are asked what they would do as a tutor or
as a learner. As tutors, AI agents are prompted to provide tutoring support --
such as generating examples, hints, and step-level correctness feedback --
which can be evaluated directly against the adaptive step-by-step support
provided by existing ITSs. As students, agents directly learn from ITS
instruction, and their mistakes and learning trajectories can be compared to
student data. TutorGym establishes a common framework for training and
evaluating diverse AI agents, including LLMs, computational models of learning,
and reinforcement learning agents, within a growing suite of learning
environments. Currently, TutorGym includes 223 different tutor domains. In an
initial evaluation, we find that current LLMs are poor at tutoring -- none did
better than chance at labeling incorrect actions, and next-step actions were
correct only ~52-70% of the time -- but they could produce remarkably
human-like learning curves when trained as students with in-context learning.
