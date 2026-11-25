# GLIMPSE

Code for the paper *Visual Stimuli Decoding from EEG Data via Contrastive Learning* (under review).

GLIMPSE is a compact EEG encoder (temporal–spatial convolutions + a single bidirectional Mamba-2 layer with temporal register read-out) for zero-shot image retrieval on THINGS-EEG2, aligned to intermediate layers of frozen CLIP image encoders.

**The code will be released here upon publication**, including:
- preprocessing of THINGS-EEG2
- extraction of CLIP intermediate-layer targets
- training and evaluation scripts
- configurations of GLIMPSE and GLIMPSE+
- the concept-disjoint validation split and the training seeds

Dataset: [THINGS-EEG2](https://osf.io/3jk45/) (Gifford et al., 2022).
