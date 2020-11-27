---
layout: default
title: SF-UDA-3D
---

# Abstract

3D object detectors based only on LiDAR point clouds hold the state-of-the-art on modern street-view benchmarks.
However, LiDAR-based detectors poorly generalize across domains due to domain shift. In the case of LiDAR, in fact, domain shift is not only due to changes in the environment and in the object appearances, as for visual data from RGB cameras, but is also related to the geometry of the point clouds (e.g., point density variations).
This paper proposes SF-UDA$^{3D}$, the first Source-Free Unsupervised Domain Adaptation (SF-UDA) framework to domain-adapt the state-of-the-art PointRCNN 3D detector to target domains for which we have no annotations (unsupervised), neither we hold images nor annotations of the source domain (source-free). SF-UDA$^{3D}$ is novel on both aspects. Our approach is based on pseudo-annotations, reversible scale-transformations and motion coherency.
SF-UDA$^{3D}$ outperforms both previous domain adaptation techniques based on features alignment and state-of-the-art 3D object detection methods which additionally use few-shot target annotations or target annotation statistics. This is demonstrated by extensive experiments on two large-scale datasets, i.e., KITTI and nuScenes.
[Full paper](https://arxiv.org/abs/2010.08243)

# Proposed Method

![Method](/images/method.png)


# Acknowledgments

The work was partially supported by OSRAM GmbH and was carried out in the Vision and Learning joint laboratory of [FBK](https://www.fbk.eu/en/) and [UNITN](http://mhug.disi.unitn.it/index.php/people/). We thank the CARITRO Deep Learning laboratory of [ProM Facility](https://polomeccatronica.it/cosa-offriamo/laboratori-prom) for the granted GPU time.


