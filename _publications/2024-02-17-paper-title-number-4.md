---
title: "SfmCAD: Unsupervised CAD Reconstruction by Learning Sketch-based Feature Modeling Operations"
collection: publications
permalink: /publication/2024-02-17-sfm-cad
excerpt: 'A new unsupervised neural network, SfmCAD, is introduced to reconstruct CAD models by learning sketch-based feature modeling operations'
date: 2024-02-27
venue: 'CVPR'
paperurl: 'http://favormylikes.github.io/files/2024_CVPR_SfmCAD_main.pdf'
header:
  teaser: https://raw.githubusercontent.com/FavorMylikes/hackmd-note/img/img2024_CVPR_SfmCAD_main.jpg
type: grid
# citation: 'Your Name, You. (2024). &quot;Paper Title Number 3.&quot; <i>GitHub Journal of Bugs</i>. 1(3).'
---

<img src="https://raw.githubusercontent.com/FavorMylikes/hackmd-note/img/img2024_CVPR_SfmCAD_main.jpg" alt="2024_CVPR_SfmCAD_main"/>

## Abstract

This paper introduces SfmCAD, a novel unsupervisednetwork that reconstructs 3D shapes by learning the SketchbasedFeature Modeling operations commonly used inmodern CAD workflows. Given a 3D shape representedas voxels, SfmCAD learns a neural-typed sketch+path parameterizedrepresentation, including 2D sketches of featureprimitives and their 3D sweeping paths without supervision, for inferring feature-based CAD programs. SfmCADemploys 2D sketches for local detail representation and 3Dpaths to capture the overall structure, achieving a clearseparation between shape details and structure. This conversioninto parametric forms enables users to seamlesslyadjust the shape’s geometric and structural features, thusenhancing interpretability and user control. We demonstratethe effectiveness of our method by applying Sfm-CAD to many different types of objects, such as CAD parts, ShapeNet objects, and tree shapes. Extensive comparisonsshow that SfmCAD produces compact and faithful 3D reconstructionswith superior quality compared to alternatives.The code is released at [SfmCAD](https://github.com/BunnySoCrazy/SfmCAD).