### Hunter Heidenreich

Senior AI Research Scientist training large language and vision models at production scale, with research roots in scientific machine learning (Harvard).

One question runs under most of my work: how to represent data on the boundary between the continuous and the discrete. FFT frequency bins, language tokens, molecular-dynamics trajectories modeled with mixture-density heads, OCR pixels fused with text, and now SMILES strings for chemistry. The same question each time; only the substrate changes.

**Selected work**

- [GutenOCR](https://github.com/Roots-Automation/GutenOCR): open-weights vision-language model family (3B and 7B) for grounded document OCR, with open training code (Apache-2.0) and the 1.5M-page [PubMed-OCR](https://huggingface.co/datasets/rootsautomation/pubmed-ocr) dataset; weights CC-BY-NC. (Led at Roots.)
- [Page Stream Segmentation with LLMs](https://aclanthology.org/2025.coling-industry.26/): COLING 2025, industry track.
- [Deconstructing Recurrence, Attention, and Gating](https://arxiv.org/abs/2410.02654): architecture transferability for forecasting chaotic dynamical systems (Harvard).
- [Where to Cut, How Deep](https://arxiv.org/abs/2607.05691): a controlled study of BPE vs Unigram-LM tokenizers on chemistry SMILES (arXiv + ChemRxiv preprint), with all trained tokenizers and [code](https://github.com/hunter-heidenreich/smiles-subword-vocabularies) released.
- [academic-tools-mcp](https://github.com/hunter-heidenreich/academic-tools-mcp): an MCP server giving agents identifier-routed tools across seven academic providers.

**Now**

Foundation-model methods for the sciences, with a focus on post-training, data, and evaluation. My most recent public work is a chemistry preprint showing that how you tokenize SMILES is a modeling decision, not a free default (all tokenizers released). Pinned repositories below span scientific computing, chemistry tooling, and research infrastructure.
