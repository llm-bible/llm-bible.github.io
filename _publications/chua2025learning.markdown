---
layout: publication
title: 'Learning Natural Language Constraints For Safe Reinforcement Learning Of Language Agents'
authors: Jaymari Chua, Chen Wang, Lina Yao
conference: "Arxiv"
year: 2025
bibkey: chua2025learning
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2504.03185'}
tags: ['Agentic', 'Security', 'Model Architecture', 'Applications', 'Tools', 'Fine-Tuning', 'Training Techniques', 'BERT', 'Reinforcement Learning', 'Responsible AI', 'Pretraining Methods']
---
Generalizable alignment is a core challenge for deploying Large Language
Models (LLMs) safely in real-world NLP applications. Current alignment methods,
including Reinforcement Learning from Human Feedback (RLHF), often fail to
guarantee constraint satisfaction outside their training distribution due to
their reliance on implicit, post-hoc preferences. Inspired by a paradigm shift
to first curate data before tuning, we introduce a new framework for safe
language alignment that learns natural language constraints from positive and
negative demonstrations as a primary step. From inferring both a task-specific
reward function and latent constraint functions, our approach fosters
adaptation to novel safety requirements and robust generalization under domain
shifts and adversarial inputs. We formalize the framework within a Constrained
Markov Decision Process (CMDP) and validate it via a text-based navigation
environment, demonstrating safe adaptation to changing danger zones. Our
experiments show fewer violations upon domain shift when following a safe
navigation path, and we achieve zero violations by applying learned constraints
to a distilled BERT model as a fine-tuning technique. This work offers a
promising path toward building safety-critical and more generalizable LLMs for
practical NLP settings.
