The Transformer struggles with longer sequences during inference, leading to high perplexity. Adjusting context length is costly. Rotary encodings show promise but have limitations. T5 models perform well but demand significant computational resources.

Alibi introduces negative biases to attention scores based on token distance, moderated by a normalization factor "m." Varying m across attention heads enables nuanced behavior, with higher values constraining attention.
