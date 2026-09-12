PyTorch Transformer From Scratch 🚀

A clean, educational, and modular implementation of the original Transformer architecture from the seminal paper "Attention Is All You Need" built entirely from scratch using PyTorch.

This repository is perfect for researchers, students, and developers who want to understand the inner workings of Transformers without relying on pre-built high-level library abstractions.


🌟 Features

Complete Architecture: Includes both the Encoder and Decoder stacks.

Custom Multi-Head Attention: Fully transparent implementation of scaled dot-product attention and head splitting/combining.

Positional Encoding: Standard sine and cosine positional encodings to inject sequence order information.

Modular Design: Components (EncoderLayer, DecoderLayer, PositionWiseFeedForward) are isolated for easy reuse or modification.

Ready-to-run Training Loop: Includes a training and validation loop using dummy data to demonstrate gradient flow and model convergence.


🏗️ Architecture Components

Multi-Head Attention (MultiHeadAttention): Computes query, key, and value representations and performs scaled dot-product attention across multiple heads.

Position-Wise Feed Forward (PositionWiseFeedForward): A two-layer linear network with a ReLU activation applied independently to each position.

Positional Encoding (PositionalEncoding): Adds positional context to the token embeddings using trigonometric functions.

Encoder & Decoder Layers: Stacks of attention and feed-forward networks wrapped with residual connections and layer normalization.
