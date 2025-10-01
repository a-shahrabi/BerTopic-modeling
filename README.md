BERTopic + Cohere Integration: Implementation Guide for Azure
Implementation plan for adding Cohere representation
Overview
This implementation adds Cohere as a second representation model after MaximalMarginalRelevance (MMR) in your BERTopic pipeline. The chain processes sequentially: c-TF-IDF → MMR (keyword diversification) → Cohere (final LLM-generated labels). 
