---
title: "Riemannian Sliced Wasserstein Distance on Correlation Matrix"
collection: publications
category: conferences
permalink: /publication/2026-riemannian-sliced-wasserstein
excerpt: 'We propose Correlation Sliced-Wasserstein (CorSW) on the manifold of full-rank correlation matrices, leveraging closed-form Busemann projections to accelerate Riemannian optimal transport (≈2× faster than non-sliced baselines) with consistent performance gains across BCI, radar recognition, and skeleton-based action recognition tasks.'
date: 2026-01-01
venue: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2026) — Under Review'
citation: '<b>Youxing, L.</b>, &amp; Zihen, C. (2026). &quot;Riemannian Sliced Wasserstein Distance on Correlation Matrix.&quot; <i>Under review at IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2026)</i>.'
---

**Review Scores:** 6/3/4 with the highest confidence 4 of the full review scores 6.

## Method & Geometric Framework

We propose **Correlation Sliced-Wasserstein (CorSW)** on the manifold of full-rank correlation matrices $$\text{Cor}_+(n)$$, leveraging closed-form Busemann projections to accelerate Riemannian optimal transport (OT) alignment (≈2× faster than non-sliced Riemannian-Wasserstein baselines) with consistent performance gains across BCI, radar recognition, and skeleton-based action recognition tasks (up to +4.46%).

## Robustness & Multimodal Applications

CorSW exploits the **scale-invariance** of correlation matrices to enhance robustness against sensor and subject variabilities. It embeds into multimodal systems to mitigate domain shift and achieve cross-modal alignment, serving as an alignment loss for non-textual modalities (EEG, radar, skeletal sequences) in representation learning and generative training, providing a tractable geometric tool for the "alignment → representation → generation" loop.
