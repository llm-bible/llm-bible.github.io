---
layout: publication
title: 'Decoding Style: Efficient Fine-tuning Of Llms For Image-guided Outfit Recommendation With Preference'
authors: Najmeh Forouzandehmehr, Nima Farrokhsiar, Ramin Giahi, Evren Korpeoglu, Kannan Achan
conference: "Arxiv"
year: 2024
bibkey: forouzandehmehr2024decoding
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2409.12150"}
tags: ['Fine-Tuning', 'Tools', 'Reinforcement Learning', 'Training Techniques', 'Pretraining Methods', 'Multimodal Models']
---
Personalized outfit recommendation remains a complex challenge, demanding
both fashion compatibility understanding and trend awareness. This paper
presents a novel framework that harnesses the expressive power of large
language models (LLMs) for this task, mitigating their "black box" and static
nature through fine-tuning and direct feedback integration. We bridge the item
visual-textual gap in items descriptions by employing image captioning with a
Multimodal Large Language Model (MLLM). This enables the LLM to extract style
and color characteristics from human-curated fashion images, forming the basis
for personalized recommendations. The LLM is efficiently fine-tuned on the
open-source Polyvore dataset of curated fashion images, optimizing its ability
to recommend stylish outfits. A direct preference mechanism using negative
examples is employed to enhance the LLM's decision-making process. This creates
a self-enhancing AI feedback loop that continuously refines recommendations in
line with seasonal fashion trends. Our framework is evaluated on the Polyvore
dataset, demonstrating its effectiveness in two key tasks: fill-in-the-blank,
and complementary item retrieval. These evaluations underline the framework's
ability to generate stylish, trend-aligned outfit suggestions, continuously
improving through direct feedback. The evaluation results demonstrated that our
proposed framework significantly outperforms the base LLM, creating more
cohesive outfits. The improved performance in these tasks underscores the
proposed framework's potential to enhance the shopping experience with accurate
suggestions, proving its effectiveness over the vanilla LLM based outfit
generation.
