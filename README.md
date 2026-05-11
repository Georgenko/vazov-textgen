# vazov-textgen
I will train sequence models with Vazov books and learn about RNNs, LSTMs, and Transformers

### Project structure
```
├── data/
│   ├── raw/          # original downloaded .txt files
│   └── processed/    # cleaned, tokenized output
├── notebooks/
└── src/              # models go here later
```

Latin characters were removed rather than replaced with an UNK token, since their ~1% frequency is insufficient for the model to learn meaningful UNK representations in a character-level setting