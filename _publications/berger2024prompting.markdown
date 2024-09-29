---
layout: publication
title: Prompting Large Language Models With Human Error Markings For Self45;correcting Machine Translation
authors: Berger Nathaniel, Riezler Stefan, Exel Miriam, Huck Matthias
conference: "Arxiv"
year: 2024
bibkey: berger2024prompting
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2406.02267"}
tags: ['Applications', 'Prompting']
---
While large language models (LLMs) pre45;trained on massive amounts of unpaired language data have reached the state45;of45;the45;art in machine translation (MT) of general domain texts post45;editing (PE) is still required to correct errors and to enhance term translation quality in specialized domains. In this paper we present a pilot study of enhancing translation memories (TM) produced by PE (source segments machine translations and reference translations henceforth called PE45;TM) for the needs of correct and consistent term translation in technical domains. We investigate a light45;weight two45;step scenario where at inference time a human translator marks errors in the first translation step and in a second step a few similar examples are extracted from the PE45;TM to prompt an LLM. Our experiment shows that the additional effort of augmenting translations with human error markings guides the LLM to focus on a correction of the marked errors yielding consistent improvements over automatic PE (APE) and MT from scratch.
