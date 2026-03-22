####  Model Architecture
Base Model: bert-base-uncased (Hugging Face Transformers)
Classification Head: A linear layer with 6 output nodes using a Sigmoid activation function for multi-label classification.
Tokenization: WordPiece tokenization with a fixed max_length of 128 tokens to balance contextual depth with computational efficiency.
Optimization: AdamW optimizer with weight decay to prevent overfitting during fine-tuning.
#### Evaluation & Metrics
The model is evaluated on the Kaggle Toxic Comment test set, with unlabelled rows ($y = -1$) strictly filtered out to ensure statistical validity.Metrics Tracked: Macro-averaged F1-Score, AUC Score,Average score
