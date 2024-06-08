---
title: "Bethany, Mazal, Brandon Wherry, Nishant Vishwamitra, and Peyman Najafirad. Image Safeguarding: Reasoning with Conditional Vision Language Model and Obfuscating Unsafe Content Counterfactually, 2024"
collection: publications
# permalink: /publication/2024-01-19-Image-Safeguarding
excerpt: 'Keywords:  Image Safeguarding'
date: 2024-01-19
venue: 'arXiv'
paperurl: 'https://arxiv.org/pdf/2401.11035'
citation: 'Mohammad Saif Wajid, Hugo Terashima-Marin, Peyman Najafirad, Santiago Enrique Conant Pablos, Mohd Anas Wajid
# Abstract: The increasing popularity of digital twins, alongside the rapid evolution of connectivity driven by the Internet of Things, highlights their potential to greatly aid in the development of smart cities. Digital twins are employed more commonly as smart cities grow and societies become more interconnected. With the growing need for this technology, there is a pressing demand for the automatic captioning of security events from the videos collected from these models. This is needed as Dtwin models generate a lot of data that makes it difficult to caption them manually. This is required for extracting rich and meaningful higher-level interpretations from images and videos. Current models often lack in-depth insights into these complex urban systems. Additionally, there is a need for a model that can interpret and explain images and videos effectively, leveraging a combination of machine learning and knowledge graph approaches. Therefore, in this paper, we developed the Digital Twin for the buildings and road network of the TEC (Tecnologico De Monterrey) district region and additionally developed the Knowledge Graph models for emulating security events with dense video captioning. This is done by designing an AI-based TEC District Digital Twin for emulating security events by leveraging knowledge graph. The proposed approach provides data and insights about the district’s operations and security. This initiative will help district planners and managers to make better decisions by analyzing the real-time data. This is supposed to contribute to increased effectiveness of district services, transparency, and an efficient infrastructure.
# Keywords: Digital Twin; Smart District; Artificial Intelligence; Knowledge Graph; Dense Captioning'
---

# Abstract
Social media platforms are being increasingly used by malicious actors to share unsafe content, such as images depicting sexual activity, cyberbullying, and self-harm. Consequently, major platforms use artificial intelligence (AI)
and human moderation to obfuscate such images to make
them safer. Two critical needs for obfuscating unsafe images is that an accurate rationale for obfuscating image regions must be provided, and the sensitive regions should be
obfuscated (e.g. blurring) for users’ safety. This process involves addressing two key problems: (1) the reason for obfuscating unsafe images demands the platform to provide an
accurate rationale that must be grounded in unsafe imagespecific attributes, and (2) the unsafe regions in the image
must be minimally obfuscated while still depicting the safe
regions. In this work, we address these key issues by first
performing visual reasoning by designing a visual reasoning model (VLM) conditioned on pre-trained unsafe image
classifiers to provide an accurate rationale grounded in unsafe image attributes, and then proposing a counterfactual
explanation algorithm that minimally identifies and obfuscates unsafe regions for safe viewing, by first utilizing an
unsafe image classifier attribution matrix to guide segmentation for a more optimal subregion segmentation followed
by an informed greedy search to determine the minimum
number of subregions required to modify the classifier’s output based on attribution score. Extensive experiments on uncurated data from social networks emphasize the efficacy
of our proposed method. We make our code available at:
https://github.com/SecureAIAutonomyLab/ConditionalVLM

[Download paper here](https://arxiv.org/pdf/2401.11035)
