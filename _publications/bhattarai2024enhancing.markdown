---
layout: publication
title: Enhancing Code Translation In Language Models With Few45;shot Learning Via Retrieval45;augmented Generation
authors: Bhattarai Manish, Santos Javier E., Jones Shawn, Biswas Ayan, Alexandrov Boian, O'malley Daniel
conference: "Arxiv"
year: 2024
bibkey: bhattarai2024enhancing
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2407.19619"}
tags: ['BERT', 'GPT', 'Model Architecture', 'Pretraining Methods', 'RAG', 'Security', 'Training Techniques']
---
The advent of large language models (LLMs) has significantly advanced the field of code translation enabling automated translation between programming languages. However these models often struggle with complex translation tasks due to inadequate contextual understanding. This paper introduces a novel approach that enhances code translation through Few45;Shot Learning augmented with retrieval45;based techniques. By leveraging a repository of existing code translations we dynamically retrieve the most relevant examples to guide the model in translating new code segments. Our method based on Retrieval45;Augmented Generation (RAG) substantially improves translation quality by providing contextual examples from which the model can learn in real45;time. We selected RAG over traditional fine45;tuning methods due to its ability to utilize existing codebases or a locally stored corpus of code which allows for dynamic adaptation to diverse translation tasks without extensive retraining. Extensive experiments on diverse datasets with open LLM models such as Starcoder Llama345;70B Instruct CodeLlama45;34B Instruct Granite45;34B Code Instruct and Mixtral45;8x22B as well as commercial LLM models like GPT45;3.5 Turbo and GPT45;4o demonstrate our approachs superiority over traditional zero45;shot methods especially in translating between Fortran and CPP. We also explored varying numbers of shots i.e. examples provided during inference specifically 1 2 and 3 shots and different embedding models for RAG including Nomic45;Embed Starencoder and CodeBERT to assess the robustness and effectiveness of our approach.
