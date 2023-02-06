# using-clip

Currently, CLIP (Contrastive Language–Image Pre-training) - a SOTA Visual Language Model - by OpenAI enables users to map between images and natural language. Howewer, to make zero-shot predictions, CLIP users have to go through a manual process of implementing, otherwise boilerplate, functionality to get a pre-trained CLIP instance up and running on a Jupyter Notebook. 

As part of this project, I would like to implement a mini Python library that will provide two main features at the ease of single function calls:

- generic functionality to compute alignment between a sequence of natural language annotations
- perform zero-shot image classification via pre-trained CLIP on an input image.

While this tool would be handy for CLIP users, I would like to enable this project to further contribute to my research, which (in a nutshell) utilizes CLIP to predict the current state of a text progression, visually and grounded by natural language. I will be brain-storming further about a helper tool that could help me (and other developers in the community using VLMs) during my research project.

For reference, CLIP by OpenAI: [link](https://openai.com/blog/clip/)
