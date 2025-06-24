# Decoder-Only Transformer from Scratch (PyTorch + Lightning)

Implements a **decoder-only transformer** from scratch using PyTorch. With clean, minimal code and no external model libraries.


* **Token Embedding:** Converts input tokens into dense vectors
* **Positional Encoding:** Adds sequence order information
* **Self-Attention Layer:** Computes attention scores from scratch (single-head/multi-head)
* **Autoregressive Training Loop:** Predicts next token in sequence

The model is trained on tiny sequences of tokenized data for quick experimentation and clarity.
