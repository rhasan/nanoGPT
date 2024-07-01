# nanoGPT
This is my attempt to following along Andrej Karpathy's Neural Networks: Zero to Hero lecture series.

The lectures cover neural networks and starts at the basics. It gradually introduces topics like training a neural network, building langauge models, transforers, and tokenizers,

---

**Lecture 1: The spelled-out intro to neural networks and backpropagation: building micrograd**

Backpropagation and training of neural networks. Assumes basic knowledge of Python and a vague recollection of calculus from high school.

- [YouTube video lecture](https://www.youtube.com/watch?v=VMj-3S1tku0)
- [Jupyter notebook files](micrograd)

---

**Lecture 2: The spelled-out intro to language modeling: building makemore**

Implementing a bigram character-level language model, which we gradually convert to a modern Transformer language model, like GPT. In this lecture, the focus is on (1) introducing torch.Tensor and its subtleties and use in efficiently evaluating neural networks and (2) the overall framework of language modeling that includes model training, sampling, and the evaluation of a loss (e.g. the negative log likelihood for classification).

- [YouTube video lecture](https://www.youtube.com/watch?v=PaCmpygFfXo)
- [Jupyter notebook files](makemore/makemore_part1_bigrams.ipynb)
