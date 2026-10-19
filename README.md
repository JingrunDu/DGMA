# DGMA

**Decoupled Geometric Manifold Alignment for 3D-Consistent Video Diffusion**

## Abstract

Videos are inherently 2D projections of a dynamic 3D world. Existing video diffusion models often suffer from severe geometric collapse and long-horizon trajectory drift during long-range generation, primarily due to their lack of explicit 3D geometric constraints. To bridge this gap, we propose Decoupled Geometric Manifold Alignment (DGMA), a framework that enforces the internalization of 3D geometric priors by aligning diffusion latents with pre-trained geometric experts. Specifically, we decouple the alignment into two synergistic components: Local Geometry Alignment, which employs cosine similarity to ensure directional consistency; and Global Topological Consistency, which distills inter-token relational dependencies through self-affinity matrices and KL divergence. To avoid empirical trial-and-error, we introduce a PCA-based heuristic to identify suitable alignment sites by combining cumulative variance analysis with qualitative feature visualization. Experiments on camera-conditioned tasks demonstrate that DGMA effectively anchors the generative process within a 3D geometric manifold, significantly enhancing the viewpoint-consistent structural integrity and long-range trajectory stability of synthesized videos.

**Keywords:** Video Diffusion Models, Geometric Manifold Alignment, 3D Consistency.

## Release Status

- Paper: **To be released.**
- Code: **To be released.**
