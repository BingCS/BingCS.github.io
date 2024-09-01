---
layout: page
title: Projects
permalink: /research/
description: Ongoing and completed research projects by SPACE Group
nav: true
nav_order: 4
---

---
<section>
  <h4>Hierarchical Intermediate Feature Description and Alignment across Point Clouds and Images without Human Annotations</h4>
  
Precisely interpreting the inherent complementarity between point clouds and images is essential for machines to effectively perceive the surrounding environment. Central to this is the careful establishment of robust and consistent associations between the two modalities. Previous methods have treated this task as fully-supervised metric learning or pose optimization problems, thus heavily relying on dense human annotations for network training. Despite impressive performance, these methods are prohibitively costly and struggle to generalize to unseen real-world scenarios. Additionally, they typically employ straightforward alignment strategies, intrinsically overlooking the feature granularity necessary for hierarchical alignment, especially in the presence of significant variations or intricate structures. 

This project aims to align point clouds and images without the need for human labels during training. This is particularly challenging and remains largely unexplored, even with the rapid advancements of full supervision methods. The primary challenge arises from the lack of intermediate features. To address this, we will derive semantic and geometric insights from raw point clouds and images, and subsequently integrate meaningful intra- and cross-modal consensuses as supervision signals for training neural networks. 

Our research will pioneer several innovative techniques. Firstly, we will design a new taskagnostic pipeline to construct unified features for aligning point clouds and images at a group level. This pipeline will serve as a bridge between the two modalities, leveraging both taskagnostic, group-coherent semantic and geometric cues to effectively identify unified features. Secondly, a novel self-supervised learning framework will be introduced to learn transferable features for patch-level alignment without human annotations. It will leverage both intra- and cross-modal transferability to infer the invariance between point cloud and image patches. Thirdly, another new self-supervised architecture will be proposed to identify point-pixel correspondences using consensus-driven features. It will harness global and cross-modal consensuses to interact these features, thereby enabling adaptive point-pixel alignment. 

This project is poised to directly advance multi-modal and self-supervised learning techniques for the interpretation and association of point clouds and images. Our methods aim to learn universal intermediate features rather than merely fitting to human labels, thus holding the potential to transform how machines perceive and integrate information across modalities. This paves the way for ground-breaking advancements in domains that require comprehensive scene understanding. Furthermore, this project is anticipated to influence cutting-edge applications such as autonomous driving, robotic manipulation, and augmented reality.
  
</section>

---
<section>
  <h4>Multi-modal Fusion for Autonomous and Intelligent Underwater Localization and Mapping</h4>

In the rapidly evolving coastal metropolises, particularly Hong Kong, Marine Surveying is critical for navigating and managing the extensive coastline and bustling port activities. The unique marine environment of Hong Kong, characterized by its strategic maritime position and heavy shipping traffic, necessitates advanced methodologies to ensure navigational safety and environmental monitoring.

This research initiative aims to transform Marine Surveying through the development and deployment of innovative and intelligent multimodal robotic systems, specifically Underwater Unmanned Vehicles (UUVs). These systems are tailored for autonomous operation in the complex marine environment of Hong Kong, incorporating state-of-the-art advancements in Spatial Perception for multimodal localization and mapping. This enables the UUVs to survey and map the marine terrain accurately, providing essential data for maritime navigation and environmental assessments. 

The impact of this research is profound, as it introduces a pioneering approach to Marine Surveying using UUVs equipped with cutting-edge technologies. By improving survey accuracy and efficiency, these systems play an essential role in promoting sustainability, mitigating safety risks, and enhancing navigational safety. This project represents a commitment to innovative and sustainable solutions, positioning the region as a leader in technological advancement in the field of underwater robotics.

Overall, multi-modal spatial perception in UUVs for Marine Surveying has the potential to advance the field of underwater robotics, contribute to research in control theory and computer vision, and result in safer, more cost-effective maritime operations. The broader impact of this research, if successfully implemented, could extend beyond Hong Kong, establishing a global standard for Marine Surveying.
  
</section>

---
<section>
  <h4>Local Feature Extraction and Matching for Cross-modal Registration</h4>
  
Accurate cross-modal registration between real-scene images and 3D point clouds is the key to ensuring the quality of spatial location services and smart city applications. The core problem in cross-modal registration is local feature extraction and matching. Existing methods mainly train dedicated neural networks for specific single-modal registration tasks, which are unable to describe the shared features between images and point clouds, detect keypoints based on a unified standard, and lack the ability to match features with global consistency. This project aims to propose a new integrated framework of cross-modal local shared feature description, keypoint detection and feature matching for real-scene image and 3D point cloud registration. Firstly, an adaptive feature description framework is constructed based on pseudo-siamese neural networks to obtain a discriminative and compact local feature description algorithm. Secondly, a self-supervised keypoint detection mechanism and corresponding implementation strategy are designed based on non-maximal suppression to obtain a unique and repeatable keypoint detection algorithm. Finally, an optimal transport feature matching model is established based on attentional graph neural networks to obtain a globally optimal and efficient feature matching algorithm. This research will effectively promote the cross fusion of cross-modal learning, metric learning and deep learning, and critically provide theoretical support and technology guarantee for the practical application of cross-modal registration methods, which has essential academic significance and broad application value.
  
</section>

---
<section>
  <h4>Unsupervised Metric-Semantic Understanding from Large-Scale 3D Point Clouds</h4>
  
Recent years have seen a growing interest towards metric-semantic understanding, which consists in building a semantically annotated (or object-oriented) model of the environment. Precisely understanding the shape and semantic compositions of large-scale 3D point clouds is crucial for machines to quickly interpret the surrounding environment. Core tasks include semantic segmentation, object detection/segmentation, surface reconstruction, etc. Previous deep learning methods consider these tasks as fully-supervised classification or regression problems, thus relying heavily on dense human annotations for training networks. Although achieving great performance, they are prohibitively costly and can hardly generalize to unseen scenarios for real-world deployment. For example, it takes 1700 person-hours to annotate a typical outdoor point cloud dataset (SemanticKITTI) and 600 person-hours an indoor dataset (ScanNet), and the models trained on an indoor dataset are barely able to generalize to outdoor scenes. 

This project aims to interpret 3D scenes without requiring any human labels in training. This is particularly challenging and highly unexplored thus far, despite the rapid progress of fullsupervision methods. Fundamentally, the challenge lies in the lack of explicit supervision signals. To address this challenge, we will introduce semantic and shape priors from raw point clouds and then integrate meaningful inductive biases as supervision signals to train neural networks. 

This research will develop several technical innovations. First, a new unsupervised pipeline will be designed to learn both 3D semantics and object instances without needing human annotations. This pipeline will exploit shape similarities to infer per-point semantic categories, and leverage motion cues to discover object boundaries. Second, a novel zero-shot learning framework will be introduced to push the boundary of segmenting open-world point clouds in which some object classes are never seen in training. This framework will utilize the semantic connection between textual and visual embeddings and then establish the proximity between seen and unseen classes. Third, another new unsupervised architecture will be proposed to recover continuous 3D surfaces only from discrete point cloud scans. This architecture will exploit the shape continuity of local regions as pseudo labels to train a surface reconstruction network. 

This project will directly advance the unsupervised and zero-shot learning techniques for analyzing large-scale point clouds. In addition, our methods are planned to learn general 3D point features instead of fitting human labels, and therefore have the potential to improve existing fullysupervised methods when integrated properly. It is also expected to have a practical impact on cutting-edge applications such as autonomous driving, navigation, and mixed reality.
  
</section>
