# Understanding Multi-Modal Speaker Recognition via Disentangled Representation Learning

This repository houses the official PyTorch implementation of USC's EE641 (Deep Learning System) course project.

## Abstract 
The primary target in supervised machine learning is to model the discriminative probability \textit{p(y$|$x)}. 
However, in the process of doing so, data samples often contain "irrelevant" factors that could mislead the model in the estimation. 
In this work, we address the problem of speaker recognition (loosely speaker classification) from a multi-modal (audio-visual) point of view 
and present an adversarial invariance approach, and propose a feature extraction pipeline, to achieve the same.  
Experimental results reveal that the multimodal learning setup achieves a relative improvement of 25.5\% in classification accuracy over using x-vectors only 
and about 0.048\% over using the frame-level features only, as the input. We achieve even superior results when the video frames are augmented with Gaussian noise, 
which makes the adversarial network even more robust to these irrelevant factors, that could have degraded the speaker recognition performance.
