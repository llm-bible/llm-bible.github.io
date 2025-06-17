---
layout: publication
title: Integrating Visuospatial, Linguistic And Commonsense Structure Into Story Visualization
authors: Adyasha Maharana, Mohit Bansal
conference: Arxiv
year: 2021
citations: 17
bibkey: maharana2021integrating
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.10834'}, {name: Code,
    url: 'https://github.com/adymaharana/VLCStoryGan'}]
tags: [Transformer, Fine-Tuning]
---
While much research has been done in text-to-image synthesis, little work has
been done to explore the usage of linguistic structure of the input text. Such
information is even more important for story visualization since its inputs
have an explicit narrative structure that needs to be translated into an image
sequence (or visual story). Prior work in this domain has shown that there is
ample room for improvement in the generated image sequence in terms of visual
quality, consistency and relevance. In this paper, we first explore the use of
constituency parse trees using a Transformer-based recurrent architecture for
encoding structured input. Second, we augment the structured input with
commonsense information and study the impact of this external knowledge on the
generation of visual story. Third, we also incorporate visual structure via
bounding boxes and dense captioning to provide feedback about the
characters/objects in generated images within a dual learning setup. We show
that off-the-shelf dense-captioning models trained on Visual Genome can improve
the spatial structure of images from a different target domain without needing
fine-tuning. We train the model end-to-end using intra-story contrastive loss
(between words and image sub-regions) and show significant improvements in
several metrics (and human evaluation) for multiple datasets. Finally, we
provide an analysis of the linguistic and visuo-spatial information. Code and
data: https://github.com/adymaharana/VLCStoryGan.