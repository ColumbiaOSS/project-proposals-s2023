# dtw-sofar

Project Repository: [link](https://github.com/egeozguroglu/dtw-sofar)

This library implements the "Dynamic Time Warping Algorithm" for multimodal research in a way it can warp the time series received "so far." In other words, it modifies the algorithm to be compatible with 'iterative stimuli' (when future points in the time series are received one by one).

One motivating application is aligning natural language annotations and video frames for research on Visual Language Models (e.g. CLIP), when the latter's embeddings are received frame by frame (e.g. we're making observations and don't have access to future frames). With "dtw-sofar," we can predict optimally matching annotations to new video frames on the fly - by relying on temporal information available "so far."
