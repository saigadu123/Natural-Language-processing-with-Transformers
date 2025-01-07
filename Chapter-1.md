# Hello Transformers

## Encoder Decoder Framework

The encoder-decoder framework is a neural network architecture commonly used for sequence-to-sequence tasks like translation and summarization. The encoder processes the input sequence, compressing it into a fixed-length representation (context vector) that captures its essential information. The decoder takes this context vector and generates the output sequence, one element at a time. Attention mechanisms are often added to improve performance by dynamically focusing on different parts of the input. This framework is widely employed in natural language processing (NLP) and other tasks requiring input-output mapping.

![Encoder-Decoder](images/Encoder-Decoder.png)

## Attention Mechanism

The attention mechanism in an encoder-decoder framework allows the decoder to focus on specific parts of the input sequence while generating each output token. Instead of relying solely on the encoder's final hidden state, it computes a weighted sum of all encoder hidden states, where the weights indicate the relevance of each input token to the current decoding step. These weights are learned dynamically based on the decoder's state and the encoder outputs. This approach helps capture long-range dependencies and improves performance on tasks like translation or summarization. Attention thus enhances flexibility and context awareness in sequence-to-sequence models.

![Attention-mechanism](images/Attention-Mechanism.png)

