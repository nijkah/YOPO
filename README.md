# You Only Pose Once

This is the official implementation of our paper, "You Only Pose Once: A Minimalist's Detection Transformer for Monocular RGB Category-level 9D Multi-Object Pose Estimation."

[[Project]](https://mikigom.github.io/YOPO-project-page/) [[Paper]](https://arxiv.org/abs/2508.14965) [[Video]](https://youtu.be/8n0QMGGdnHE)

Code will be released after acceptance.

## Abstract
Accurately recovering the full 9-DoF pose of unseen instances within specific categories from a single RGB image remains a core challenge for robotics and automation. Most existing solutions still rely on pseudo-depth, CAD models, or multi-stage cascades that separate 2D detection from pose estimation. Motivated by the need for a simpler, RGB-only alternative that learns directly at the category level, we revisit a longstanding question: Can object detection and 9-DoF pose estimation be unified with high performance, without any additional data? We show that they can with our method, YOPO, a single-stage, query-based framework that treats category-level 9-DoF estimation as a natural extension of 2D detection. YOPO augments a transformer detector with a lightweight pose head, a bounding-box-conditioned translation module, and a 6D-aware Hungarian matching cost. The model is trained end-to-end only with RGB images and category-level pose labels. Despite its minimalist design, YOPO sets a new state of the art on three benchmarks. On the REAL275 dataset, it achieves 79.6%  and 54.1% under the  metric, surpassing prior RGB-only methods and closing much of the gap to RGB-D systems. The code, models, and additional qualitative results can be found on our project.

## Reference
```
@article{lee2025yopo,
  title     = {You Only Pose Once: A Minimalist’s Detection Transformer for Monocular RGB Category-level 9D Multi-Object Pose Estimation},
  author    = {Hakjin Lee and Junghoon Seo and Jaehoon Sim},
  journal   = {arXiv preprint arXiv:2508.14965},
  year      = {2025}
}
```
