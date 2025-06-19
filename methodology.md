---
layout: default
title: Methodology
---

# 🧠 Methodology

The Sliding Annulus Graph Embedding (SAnnGE) project focuses on embedding convex graphs by:

1. **Graph preprocessing:** Cleaning and normalizing the input graph data.  
2. **Annulus construction:** Defining sliding annuli to capture local metric properties.  
3. **Embedding optimization:** Learning embeddings via convex projections in target metric spaces (SPD matrices, hyperbolic space, or ℓ₁ spaces).  

```python
def sliding_annulus_embed(graph):
    # Pseudocode example
    annuli = construct_annuli(graph)
    embedding = optimize_embedding(annuli)
    return embedding
```