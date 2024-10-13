---
layout: publication
title: 'Statically Contextualizing Large Language Models With Typed Holes'
authors: Blinn Andrew, Li Xiang, Kim June Hyung, Omar Cyrus
conference: "Arxiv"
year: 2024
bibkey: blinn2024statically
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.00921"}
tags: ['Applications', 'Prompting', 'Reinforcement Learning', 'Training Techniques']
---
Large language models (LLMs) have reshaped the landscape of program
synthesis. However, contemporary LLM-based code completion systems often
hallucinate broken code because they lack appropriate context, particularly
when working with definitions not in the training data nor near the cursor.
This paper demonstrates that tight integration with the type and binding
structure of a language, as exposed by its language server, can address this
contextualization problem in a token-efficient manner. In short, we contend
that AIs need IDEs, too! In particular, we integrate LLM code generation into
the Hazel live program sketching environment. The Hazel Language Server
identifies the type and typing context of the hole being filled, even in the
presence of errors, ensuring that a meaningful program sketch is always
available. This allows prompting with codebase-wide contextual information not
lexically local to the cursor, nor necessarily in the same file, but that is
likely to be semantically local to the developer's goal. Completions
synthesized by the LLM are then iteratively refined via further dialog with the
language server. To evaluate these techniques, we introduce MVUBench, a dataset
of model-view-update (MVU) web applications. These applications serve as
challenge problems due to their reliance on application-specific data
structures. We find that contextualization with type definitions is
particularly impactful. After introducing our ideas in the context of Hazel we
duplicate our techniques and port MVUBench to TypeScript in order to validate
the applicability of these methods to higher-resource languages. Finally, we
outline ChatLSP, a conservative extension to the Language Server Protocol (LSP)
that language servers can implement to expose capabilities that AI code
completion systems of various designs can use to incorporate static context
when generating prompts for an LLM.
