---
title: "Revisiting pre-trained remote sensing model benchmarks: resizing and normalization matters"
collection: publications
permalink: /publication/2024-04-01-revisiting-pre-trained-remote-sensing-model-benmarks
excerpt: 'Keywords: Computer Vision and Pattern Recognition'
date: 2024-04-01
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2305.13456'
# citation: 'Mohammad Saif Wajid, Hugo Terashima-Marin, Peyman Najafirad, Santiago Enrique Conant Pablos, Mohd Anas Wajid
# Abstract: The increasing popularity of digital twins, alongside the rapid evolution of connectivity driven by the Internet of Things, highlights their potential to greatly aid in the development of smart cities. Digital twins are employed more commonly as smart cities grow and societies become more interconnected. With the growing need for this technology, there is a pressing demand for the automatic captioning of security events from the videos collected from these models. This is needed as Dtwin models generate a lot of data that makes it difficult to caption them manually. This is required for extracting rich and meaningful higher-level interpretations from images and videos. Current models often lack in-depth insights into these complex urban systems. Additionally, there is a need for a model that can interpret and explain images and videos effectively, leveraging a combination of machine learning and knowledge graph approaches. Therefore, in this paper, we developed the Digital Twin for the buildings and road network of the TEC (Tecnologico De Monterrey) district region and additionally developed the Knowledge Graph models for emulating security events with dense video captioning. This is done by designing an AI-based TEC District Digital Twin for emulating security events by leveraging knowledge graph. The proposed approach provides data and insights about the district’s operations and security. This initiative will help district planners and managers to make better decisions by analyzing the real-time data. This is supposed to contribute to increased effectiveness of district services, transparency, and an efficient infrastructure.
# Keywords: Digital Twin; Smart District; Artificial Intelligence; Knowledge Graph; Dense Captioning'
---

# Abstract
Research in self-supervised learning (SSL) with natural images has progressed
rapidly in recent years and is now increasingly being applied to and benchmarked
with datasets containing remotely sensed imagery. A common benchmark case is to
evaluate SSL pre-trained model embeddings on datasets of remotely sensed imagery
with small patch sizes, e.g., 32 × 32 pixels, whereas standard SSL pre-training takes
place with larger patch sizes, e.g., 224 × 224. Furthermore, pre-training methods
tend to use different image normalization preprocessing steps depending on the
dataset. In this paper, we show, across seven satellite and aerial imagery datasets
of varying resolution, that by simply following the preprocessing steps used in
pre-training (precisely, image sizing and normalization methods), one can achieve
significant performance improvements when evaluating the extracted features on
downstream tasks – an important detail overlooked in previous work in this space.
We show that by following these steps, ImageNet pre-training remains a competitive
baseline for satellite imagery based transfer learning tasks – for example we find
that these steps give +32.28 to overall accuracy on the So2Sat random split dataset
and +11.16 on the EuroSAT dataset. Finally, we report comprehensive benchmark
results with a variety of simple baseline methods for each of the seven datasets,
forming an initial benchmark suite for remote sensing imagery.2

[Download paper here](https://arxiv.org/pdf/2305.13456)
