---
layout: publication
title: Code-Aware Prompting A study of Coverage Guided Test Generation in Regression Setting using LLM
authors: Ryan Gabriel, Jain Siddhartha, Shang Mingyue, Wang Shiqi, Ma Xiaofei, Ramanathan Murali Krishna, Ray Baishakhi
conference: "Arxiv"
year: 2024
bibkey: ryan2024code
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2402.00097"}
tags: ['ARXIV', 'Applications', 'GPT', 'LLM', 'Prompting', 'RAG', 'Tools', 'Training Techniques']
---
Testing plays a pivotal role in ensuring software quality yet conventional Search Based Software Testing (SBST) methods often struggle with complex software units achieving suboptimal test coverage. Recent works using large language models (LLMs) for test generation have focused on improving generation quality through optimizing the test generation context and correcting errors in model outputs but use fixed prompting strategies that prompt the model to generate tests without additional guidance. As a result LLM-generated testsuites still suffer from low coverage. In this paper we present SymPrompt a code-aware prompting strategy for LLMs in test generation. SymPrompts approach is based on recent work that demonstrates LLMs can solve more complex logical problems when prompted to reason about the problem in a multi-step fashion. We apply this methodology to test generation by deconstructing the testsuite generation process into a multi-stage sequence each of which is driven by a specific prompt aligned with the execution paths of the method under test and exposing relevant type and dependency focal context to the model. Our approach enables pretrained LLMs to generate more complete test cases without any additional training. We implement SymPrompt using the TreeSitter parsing framework and evaluate on a benchmark challenging methods from open source Python projects. SymPrompt enhances correct test generations by a factor of 5 and bolsters relative coverage by 26 for CodeGen2. Notably when applied to GPT-4 SymPrompt improves coverage by over 2x compared to baseline prompting strategies.
