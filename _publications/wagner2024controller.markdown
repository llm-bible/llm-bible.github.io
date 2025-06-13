---
layout: publication
title: 'CELI: Controller-embedded Language Model Interactions'
authors: Jan-samuel Wagner, Dave Decaprio, Abishek Chiffon Muthu Raja, Jonathan M. Holman, Lauren K. Brady, Sky C. Cheung, Hosein Barzekar, Eric Yang, Mark Anthony Ii Martinez, David Soong, Sriram Sridhar, Han Si, Brandon W. Higgs, Hisham Hamadeh, Scott Ogden
conference: "Arxiv"
year: 2024
bibkey: wagner2024controller
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2410.14627"}
tags: ['Tools', 'GPT', 'Efficiency and Optimization', 'Applications', 'Model Architecture', 'Reinforcement Learning', 'Prompting']
---
We introduce Controller-Embedded Language Model Interactions (CELI), a
framework that integrates control logic directly within language model (LM)
prompts, facilitating complex, multi-stage task execution. CELI addresses
limitations of existing prompt engineering and workflow optimization techniques
by embedding control logic directly within the operational context of language
models, enabling dynamic adaptation to evolving task requirements. Our
framework transfers control from the traditional programming execution
environment to the LMs, allowing them to autonomously manage computational
workflows while maintaining seamless interaction with external systems and
functions. CELI supports arbitrary function calls with variable arguments,
bridging the gap between LMs' adaptive reasoning capabilities and conventional
software paradigms' structured control mechanisms. To evaluate CELI's
versatility and effectiveness, we conducted case studies in two distinct
domains: code generation (HumanEval benchmark) and multi-stage content
generation (Wikipedia-style articles). The results demonstrate notable
performance improvements across a range of domains. CELI achieved a 4.9
percentage point improvement over the best reported score of the baseline GPT-4
model on the HumanEval code generation benchmark. In multi-stage content
generation, 94.4% of CELI-produced Wikipedia-style articles met or exceeded
first draft quality when optimally configured, with 44.4% achieving high
quality. These outcomes underscore CELI's potential for optimizing AI-driven
workflows across diverse computational domains.
