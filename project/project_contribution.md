# Issue to solve:

[link](https://github.com/PetrochukM/PyTorch-NLP/issues/109)

 It'd be helpful if the vocab could be generated on demand during training time. This means that we'd need to create a related embedding table that would grow during training time, as need be.

With such a system, we wouldn't need to initially load and tokenize the data.

In order to accomplish this, either the Embedding or the TokenEnum would need to also handle updating the optimizer and any related object that depends on model parameters.