---
layout: publication
title: 'Thinking Longer, Not Larger: Enhancing Software Engineering Agents Via Scaling Test-time Compute'
authors: Yingwei Ma, Yongbin Li, Yihong Dong, Xue Jiang, Rongyu Cao, Jue Chen, Fei Huang, Binhua Li
conference: "Arxiv"
year: 2025
bibkey: ma2025thinking
additional_links:
  - {name: "Paper", url: 'https://arxiv.org/abs/2503.23803'}
  - {name: "Code", url: 'https://github.com/yingweima2022/SWE-Reasoner'}
tags: ['Agentic', 'Has Code', 'RAG', 'Training Techniques', 'Tools', 'Prompting', 'Reinforcement Learning']
---
Recent advancements in software engineering agents have demonstrated
promising capabilities in automating program improvements. However, their
reliance on closed-source or resource-intensive models introduces significant
deployment challenges in private environments, prompting a critical question:
\textit\{How can personally deployable open-source LLMs achieve comparable code
reasoning performance?\}
  To this end, we propose a unified Test-Time Compute scaling framework that
leverages increased inference-time computation instead of larger models. Our
framework incorporates two complementary strategies: internal TTC and external
TTC. Internally, we introduce a \textit\{development-contextualized trajectory
synthesis\} method leveraging real-world software repositories to bootstrap
multi-stage reasoning processes, such as fault localization and patch
generation. We further enhance trajectory quality through rejection sampling,
rigorously evaluating trajectories along accuracy and complexity. Externally,
we propose a novel \textit\{development-process-based search\} strategy guided by
reward models and execution verification. This approach enables targeted
computational allocation at critical development decision points, overcoming
limitations of existing "end-point only" verification methods.
  Evaluations on SWE-bench Verified demonstrate our \textbf\{32B model achieves
a 46% issue resolution rate\}, surpassing significantly larger models such as
DeepSeek R1 671B and OpenAI o1. Additionally, we provide the empirical
validation of the test-time scaling phenomenon within SWE agents, revealing
that \textbf\{models dynamically allocate more tokens to increasingly
challenging problems\}, effectively enhancing reasoning capabilities. We
publicly release all training data, models, and code to facilitate future
research. https://github.com/yingweima2022/SWE-Reasoner
