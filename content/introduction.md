# 😊 Introduction

![alt text](images/image_examples.png)

Visual Question Answering (VQA) is a challenging task that requires AI systems to understand and reason about both visual and textual information to answer questions about an image. While recent years have witnessed significant progress in this field (Lei et al., 2018; Radford et al., 2021; Liu et al., 2023), there are still major limitations for the current CQA datasets:

1. They are primarily **focused on English** and a few major world languages.
2. The images in these datasets predominantly reflect Western scenes, **lacking the diversity** needed to represent real-world scenarios across different cultures.
3. There is often a **mismatch between the language and image style** resulting in image-content incongruence across languages.

To address these limitations, we propose building a <b><span style='color: red'>culturally-and-linguistically diverse multilingual multimodal VQA benchmark, with the aim of promoting fairness, by ensuring that all languages, especially low-resource ones, are adequately represented</span></b>. By incorporating culturally-specific questions and images, CVQA will better represent real-world scenarios and improve the robustness of VQA models through training on diverse data.

Specifically, we gather the help from peers across the whole ACL community to obtain culturally-diverse images and questions in the corresponding local languages to ensure the language style does match the image style. In the first round of data collection, we get around 5k images and 10k questions, covering more than 30 countries which are under-represented in previous VQA datasets. 
