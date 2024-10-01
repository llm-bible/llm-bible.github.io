---
layout: publication
title: 'Looking For A Needle In A Haystack: A Comprehensive Study Of Hallucinations In Neural Machine Translation'
authors: Guerreiro Nuno M., Voita Elena, Martins André F. T.
conference: "Arxiv"
year: 2022
bibkey: guerreiro2022looking
additional_links:
  - {name: "Paper", url: "https://arxiv.org/abs/2208.05309"}
tags: ['Applications', 'Attention Mechanism', 'Model Architecture', 'Training Techniques']
---
"Although the problem of hallucinations in neural machine translation (NMT) has received some attention, research on this highly pathological phenomenon lacks solid ground. Previous work has been limited in several ways: it often resorts to artificial settings where the problem is amplified, it disregards some (common) types of hallucinations, and it does not validate adequacy of detection heuristics. In this paper, we set foundations for the study of NMT hallucinations. First, we work in a natural setting, i.e., in-domain data without artificial noise neither in training nor in inference. Next, we annotate a dataset of over 3.4k sentences indicating different kinds of critical errors and hallucinations. Then, we turn to detection methods and both revisit methods used previously and propose using glass-box uncertainty-based detectors. Overall, we show that for preventive settings, (i) previously used methods are largely inadequate, (ii) sequence log-probability works best and performs on par with reference-based methods. Finally, we propose DeHallucinator, a simple method for alleviating hallucinations at test time that significantly reduces the hallucinatory rate. To ease future research, we release our annotated dataset for WMT18 German-English data, along with the model, training data, and code."
