# Long-Context Attention Hub

A general-purpose toolkit for efficient attention in long-sequence transformers.
It implements FlashAttention-2, sliding-window attention and block-sparse attention.

## Reference
- Paper: FlashAttention-2: Faster Attention with Better Parallelism and Work Partitioning
- Preprint: arXiv:2307.08691

> Dilated Token Routing is mentioned in our related-work notes as a neighbouring
> idea, but this toolkit does not implement it and ships no DTR code.

Topics: long-context, sparse-attention, token-routing, efficient-transformers
