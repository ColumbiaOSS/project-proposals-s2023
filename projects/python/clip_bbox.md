
# CLIP_BBox

[![](https://img.shields.io/badge/project-link-green)](https://github.com/graceduansu/clip_bbox)

## Description

`CLIP_BBox` is a Python library for detecting image objects with natural language text labels.

[CLIP](https://github.com/openai/CLIP) is a neural network, pretrained on image-text pairs, that can predict the most relevant text snippet for a given image.

Given an image and a natural language text label, CLIP_BBox will obtain the image's spatial embedding and text label's embedding from CLIP, compute the similarity heatmap between the embeddings, then draw a bounding box around the image region with the highest image-text correspondence.

The library will provide functions for the following operations:

* Getting and appropriately reshaping an image's spatial embedding from the CLIP model before it performs attention-pooling
* Getting a text snippet's embedding from the CLIP model
* Computing the similarity heatmap between a pair of spatial and text embeddings from CLIP
* Drawing bounding boxes on an image, given a similarity heatmap and a similarity threshold
