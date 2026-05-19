# vazov-textgen
I will train sequence models with Vazov books and learn about RNNs, LSTMs, and Transformers

### Project structure
```
├── data/
│   ├── raw/          # original downloaded .txt files
│   ├── processed/    # cleaned, tokenized output (output of notebook 1)
│   ├── datasets/     # encoded splits ready for training (output of notebook 2)
│   └── vocab/        # vocab/tokenizer artifacts (output of notebook 2)
├── notebooks/
└── src/              # models go here later
```

Latin characters were removed rather than replaced with an UNK token, since their ~1% frequency is insufficient for the model to learn meaningful UNK representations in a character-level setting