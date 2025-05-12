# LLM from Scratch

This project implements a GPT-like language model from scratch, following the book *LLMs from Scratch* by [Sebastian Raschka](https://github.com/rasbt). The implementation is based on the accompanying [LLMs-from-scratch GitHub repository](https://github.com/rasbt/LLMs-from-scratch) and focuses on building a transformer-based model inspired by GPT-2, with support for loading pre-trained weights and generating text. The core implementation is provided in a Jupyter Notebook, designed for interactive experimentation, particularly in environments like Google Colab.

## Features
- Implementation of a GPT model with multi-head attention, feed-forward networks, and layer normalization.
- Support for loading pre-trained GPT-2 weights (small, medium, large, and XL models).
- Text generation with customizable parameters like temperature and top-k sampling.
- Dataset handling for training with tokenized text.
- Integration with Google Drive for saving and loading model weights.
- Fine-tuned model loading for supervised fine-tuning (SFT).

## Credits
- This project is heavily based on *LLMs from Scratch* by [Sebastian Raschka](https://github.com/rasbt).
- The implementation follows the code and explanations from the [LLMs-from-scratch repository](https://github.com/rasbt/LLMs-from-scratch).
- GPT-2 weights are sourced from the original GPT-2 model by OpenAI.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
