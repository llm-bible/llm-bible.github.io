---
layout: publication
title: ()^() A Simple Society Of Language Models Solves Complex Reasoning
authors: Juneja Gurusha, Dutta Subhabrata, Chakraborty Tanmoy
conference: "Arxiv"
year: 2024
bibkey: juneja2024simple
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2404.02255"}
  - {name: "Code", url: "https://github.com/LCS2-IIITD/Language_Model_Multiplex)"}
tags: ['Has Code', 'Pretraining Methods', 'Security']
---
Despite demonstrating emergent reasoning abilities Large Language Models (LLMS) often lose track of complex multi-step reasoning. Existing studies show that providing guidance via decomposing the original question into multiple subproblems elicits more robustness in LLM reasoning -- a decomposer generates the subproblems and a solver solves each of these subproblems. However these techniques fail to accommodate coordination between the decomposer and the solver modules (either in a single model or different specialized ones) -- the decomposer does not keep track of the ability of the solver to follow the decomposed reasoning. In this paper we propose LM2 to address these challenges. LM2 modularizes the decomposition solution and verification into three different language models. The decomposer module identifies the key concepts necessary to solve the problem and generates step-by-step subquestions according to the reasoning requirement. The solver model generates the solution to the subproblems that are then checked by the verifier module; depending upon the feedback from the verifier the reasoning context is constructed using the subproblems and the solutions. These models are trained to coordinate using policy learning. Exhaustive experimentation suggests the superiority of LM2 over existing methods on in- and out-domain reasoning problems outperforming the best baselines by 8.137; on MATH 7.7137; on JEEBench and 9.737; on MedQA problems (code available at https://github.com/LCS2-IIITD/Language\_Model\_Multiplex)."
