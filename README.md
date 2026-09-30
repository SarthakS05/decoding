# Decoding

Examples of text generation with GPT-2 using different decoding strategies through Hugging Face Transformers and TensorFlow.

The script demonstrates:

- Greedy search
- Beam search, including n-gram repetition blocking and multiple returned beams
- Sampling with temperature
- Top-k sampling
- Top-p (nucleus) sampling

## Requirements

Python, TensorFlow, and Transformers are required. Install the packages with:

```bash
python -m pip install tensorflow transformers
```

The first run downloads the GPT-2 tokenizer and model weights.

## Run

```bash
python decoding.py
```
