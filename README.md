# GPT-1 Style Character-Level Language Model

A from-scratch implementation of a **GPT-1–style Transformer** using **PyTorch**, trained at the **character level** on the Tiny Shakespeare dataset.

The project focuses on understanding **self-attention, multi-head attention, and autoregressive text generation**.

---

## Features
- Transformer-based GPT architecture
- Multi-Head Self-Attention
- Positional embeddings
- Residual connections + LayerNorm
- Dropout & AdamW optimizer
- CUDA support (if available)

---

## Dataset
- **Tiny Shakespeare**
- Character-level tokenization
- Auto-downloaded if not present

---

## Run
```bash
pip install torch
python train.py
```
