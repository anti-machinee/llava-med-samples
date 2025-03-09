# Abstract
- Achievements
    - Train a LMM in 15 hours with 8 A100 GPUs
- Solution
    - Extract figure caption data from PubMed Central
    - Self instruct open ended instruction following data from the captions
    - Fine tune a large general domain VLM using **novel curriculum learning** method
- Others
    - Firstly, model learns to algin biomedical vocab using figure caption pair and then Learn to master open ended conversational semantics

# References
- [1] https://arxiv.org/abs/2306.00890