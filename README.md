# Learnable Harmonic Variable-Q Transform (LHVQT)
Master's Thesis:
[End-to-End Music Transcription Using Fine-Tuned Variable-Q Filterbanks](https://scholarworks.rit.edu/theses/10143/)

I hypothesized that replacing standard time-frequency calculations with learned filterbank modules could improve the feature extraction stage for various Music Information Retrieval (MIR) scenarios, especially if the filterbank learning modules were initialized with weights identical to the standard transforms.

Regrettably, I chose one of the hardest problems, Automatic Music Transcription (AMT), initially to demonstrate my idea. For this task, with my initial experiments, I was not able to improve the baseline approach. Essentially, my experiments were modeled after that of the [MAESTRO paper](https://arxiv.org/abs/1810.12247) by Google, using a [PyTorch implementation](https://github.com/jongwook/onsets-and-frames) written by Jong Wook Kim.

## Citation
Cwitkowitz, Frank C. Jr, "End-to-End Music Transcription Using Fine-Tuned Variable-Q Filterbanks" (2019). Thesis. Rochester Institute of Technology.
