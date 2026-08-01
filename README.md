### Hunter Heidenreich

Senior AI Research Scientist at Bevaya.ai (formerly Roots Automation). I train language and vision-language models at production scale, and the work centers on the data and evaluation side of it: benchmark construction, annotation design, calibration. Research roots in scientific machine learning at Harvard.

The through-line is representation on the boundary between the continuous and the discrete. FFT frequency bins, language tokens, molecular-dynamics trajectories under mixture-density heads, OCR pixels fused with text, now SMILES strings. Only the substrate changes.

**Selected work**

- **[GutenOCR](https://github.com/Roots-Automation/GutenOCR)**: open-weights 3B and 7B vision-language models for grounded document OCR, with Apache-2.0 training code and the 1.5M-page [PubMed-OCR](https://huggingface.co/datasets/bevaya/pubmed-ocr) corpus. I led the model line and owned evaluation end to end, authoring the protocol that separates content from layout; the composite more than doubled over the Qwen2.5-VL backbone, 0.35 to 0.81.
- **[Where to cut, how deep](https://arxiv.org/abs/2607.05691)**: sole-authored controlled study of BPE against Unigram-LM on chemistry SMILES, showing the two build near-disjoint vocabularies over the same chemistry base. 44 trained tokenizers on [Zenodo](https://doi.org/10.5281/zenodo.21228245), with [code](https://github.com/hunter-heidenreich/smiles-subword-vocabularies) and an [interactive demo](https://huggingface.co/spaces/hheiden/smiles-subword-vocabularies).
- **[Page Stream Segmentation with LLMs](https://aclanthology.org/2025.coling-industry.26/)**: COLING 2025, industry track, on deploying LLM document automation and the calibration risk of model overconfidence. The [underlying evaluation](https://arxiv.org/abs/2408.11981) was the first systematic study of decoder-only LLMs on the task: a fine-tuned Mistral-7B segments 80% of document streams perfectly with no human intervention, 12x the best encoder baseline.
- **[Deconstructing Recurrence, Attention, and Gating](https://arxiv.org/abs/2410.02654)**: architecture transferability for forecasting chaotic dynamical systems, from Harvard's CSElab.
- Earlier first-author work on universal adversarial triggers in GPT-2 (AIES 2021) and unsupervised semantic network induction (W-NUT 2019).

Now working toward foundation models for the sciences, with a focus on post-training, data, and evaluation. Full publication list on [Google Scholar](https://scholar.google.com/citations?user=pwRTY1oAAAAJ).
