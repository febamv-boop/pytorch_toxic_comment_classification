### Model Architecture
Base Model: bert-base-uncased (Hugging Face Transformers)
Classification Head: A linear layer with 6 output nodes using a Sigmoid activation function for multi-label classification.
Tokenization: WordPiece tokenization with a fixed max_length of 128 tokens to balance contextual depth with computational efficiency.
Optimization: AdamW optimizer with weight decay to prevent overfitting during fine-tuning.
