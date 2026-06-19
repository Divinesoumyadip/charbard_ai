# CharBard

A small character-level GPT trained from scratch, based on
[nanoGPT](https://github.com/karpathy/nanoGPT) by Andrej Karpathy (MIT License).

## About
CharBard is a tiny character-level transformer trained on Shakespeare text.
A learning project to understand how language models work end-to-end.

## Run it
\\\
pip install torch numpy transformers datasets tiktoken wandb tqdm
python data/shakespeare_char/prepare.py
python train.py config/train_shakespeare_char.py --device=cpu --compile=False
python sample.py --out_dir=out-shakespeare-char --device=cpu
\\\

## Credit
Based on nanoGPT by @karpathy (MIT License).
