# Resource-Efficient-Deep-Learning-Hub

Welcome to the Resource-Efficient Deep Learning Hub!  

This repository is dedicated to aggregating milestone papers, open-source libraries, and key resources focused on resource efficiency.

---

## 🏷️ Label Descriptions

Below are the descriptions for each label used in the tables:

- **Novel algorithms**: New methods or architectures proposed to improve resource efficiency.
- **Training paradigms**: Strategies or techniques used during model training to reduce computational cost or memory usage.
- **Learning paradigms**: Approaches to how models learn, such as self-supervised or transfer learning, that impact efficiency.
- **Prompting paradigms**: Methods involving prompts (e.g., in transformers) to guide efficient learning or inference.
- **Hardware optimization techniques**: Approaches that leverage hardware features or design for better resource management.
- **Deployment**: Methods and tools focused on making models efficient for real-world deployment on resource-constrained devices.
- **Pruning**: Techniques for removing unnecessary weights or neurons from neural networks to reduce size and computation.
- **Quantization**: Approaches for reducing the precision of weights and activations to save memory and speed up inference.
- **Knowledge distillation**: Techniques where a smaller model is trained to mimic a larger one, improving efficiency.
- **Clustering**: Methods for grouping similar weights or structures in models to reduce redundancy.

---

## 📄 Milestone Papers

| Title | Year | Key Highlights | Label(s) | Repository / URL |
|-------|------|----------------|----------|------------------|
| MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications | 2017 | Introduces depthwise separable convolutions for reduced computation and memory. | Novel algorithms, Hardware optimization techniques, Deployment | [Paper](https://arxiv.org/abs/1704.04861) |
| EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks | 2019 | Compound scaling of depth, width, and resolution for better accuracy/efficiency tradeoff. | Novel algorithms, Training paradigms, Hardware optimization techniques | [Paper](https://arxiv.org/abs/1905.11946) |
| FastVLM: Efficient Vision Encoding for Vision Language Models | 2025 | Hybrid FastViTHD vision encoder; reports up to 85× faster TTFT and 3.4× smaller vision encoder vs LLaVA-OneVision-0.5B. | Novel algorithms, Deployment, Hardware optimization techniques |[Paper](https://arxiv.org/abs/2412.13303)|

> NOTE: FastVLM links are placeholders pending the public release of the official paper/repository. Feel free to update once identifiers are known.

---

## 🛠️ Open Source Libraries/Frameworks

| Name | Description | Key Highlights | Label(s) | Repository / URL |
|------|-------------|----------------|----------|------------------|
| TensorFlow Model Optimization Toolkit | Tools and APIs to optimize ML models for deployment and efficiency. | Supports quantization, pruning, clustering. | Hardware optimization techniques, Training paradigms, Pruning, Quantization, Clustering | [GitHub](https://github.com/tensorflow/model-optimization) |
| Distiller | Python package for neural network compression research. | Pruning, quantization, knowledge distillation. | Training paradigms, Learning paradigms, Pruning, Quantization, Knowledge distillation | [Distiller](https://github.com/IntelLabs/distiller) |
| FastVLM | Official (planned) implementation of FastVLM for efficient vision encoding in VLMs. | Hybrid FastViTHD encoder, multi-size variants (0.5B, 1.5B, 7B), potential mobile deployment. | Novel algorithms, Deployment, Hardware optimization techniques | [Repository](https://github.com/apple/ml-fastvlm)|

> If you know the official FastVLM repository, please replace the placeholder link.

---

## 🚀 How to Contribute

- Add new entries to the tables above by filling in the relevant details.
- For papers, include the title, year, key highlights, label(s) (e.g., novel algorithms, training, learning, prompting paradigms, hardware optimization techniques), and link to the repository/paper.
- For libraries/frameworks, include the name, a short description, main highlights, label(s), and the repository URL.
- Prefer primary sources (official papers/repos) over third-party implementations when possible.
- Keep labels concise and re-use existing categories before introducing new ones.

---

Feel free to expand and customize this template as your collection grows!
