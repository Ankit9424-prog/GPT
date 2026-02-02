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
python gpt.py
```

## Sample Output
<img width="573" height="789" alt="Screenshot 2026-02-02 193651" src="https://github.com/user-attachments/assets/92bf9128-731a-43f0-83d5-b72f24328844"/>

--- 

## Future Improvements
- Upgrade architecture toward GPT-2
- Switch to BPE / subword tokenization
- Increase model depth, width, and context length
- Add learning rate scheduling and gradient clipping
- Implement better sampling (temperature, top-k, top-p)

---

## Acknowledgements
- Inspired by Andrej Karpathy’s GPT tutorial
- Tiny Shakespeare dataset by Karpathy
