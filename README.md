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

| Title | Year | Key Highlights | Label(s) | URL |
|-------|------|----------------|----------|------------------|
| MobileNets: Efficient Convolutional Neural Networks for Mobile Vision Applications | 2017 | Introduces depthwise separable convolutions for reduced computation and memory. | Novel algorithms, Hardware optimization techniques, Deployment | [Paper](https://arxiv.org/abs/1704.04861) |
| EfficientNet: Rethinking Model Scaling for Convolutional Neural Networks | 2019 | Compound scaling of depth, width, and resolution for better accuracy/efficiency tradeoff. | Novel algorithms, Training paradigms, Hardware optimization techniques | [Paper](https://arxiv.org/abs/1905.11946) |
| FastVLM: Efficient Vision Encoding for Vision Language Models | 2025 | Hybrid FastViTHD vision encoder; reports up to 85× faster TTFT and 3.4× smaller vision encoder vs LLaVA-OneVision-0.5B. | Novel algorithms, Deployment, Hardware optimization techniques |[Paper](https://arxiv.org/abs/2412.13303)|

---

## 🛠️ Open Source Libraries/Frameworks

| Name | Description | Key Highlights | Label(s) | URL |
|------|-------------|----------------|----------|------------------|
| TensorFlow Model Optimization Toolkit | Tools and APIs to optimize ML models for deployment and efficiency. | Supports quantization, pruning, clustering. | Hardware optimization techniques, Training paradigms, Pruning, Quantization, Clustering | [GitHub](https://github.com/tensorflow/model-optimization) |
| Distiller | Python package for neural network compression research. | Pruning, quantization, knowledge distillation. | Training paradigms, Learning paradigms, Pruning, Quantization, Knowledge distillation | [GitHub](https://github.com/IntelLabs/distiller) |
| Torch-Pruning | Flexible, graph-aware structural pruning toolkit (DepGraph) supporting CNNs, Transformers, LLMs, and vision foundation models. | Implements dependency graph–based structured pruning; adaptable to diverse architectures (LLMs, vision); MIT licensed. | Pruning, Training paradigms | [GitHub](https://github.com/VainF/Torch-Pruning) |
| Torch-Pruning | Flexible, graph-aware structural pruning toolkit (DepGraph) supporting CNNs, Transformers, LLMs, and vision foundation models. | Implements dependency graph–based structured pruning; adaptable to diverse architectures (LLMs, vision); MIT licensed. | Pruning, Training paradigms | [GitHub](https://github.com/VainF/Torch-Pruning) |
| NVIDIA TensorRT Model Optimizer | A unified library of state-of-the-art model optimization techniques like quantization, pruning, distillation, speculative decoding, etc. It compresses deep learning models for downstream deployment frameworks like TensorRT-LLM or TensorRT to optimize inference speed. | Supports quantization, pruning, knowledge distillation, speculative decoding for TensorRT deployment. | Hardware optimization techniques, Deployment, Pruning, Quantization, Knowledge distillation |  [GitHub](https://github.com/NVIDIA/TensorRT-Model-Optimizer) |

---

## 🚀 How to Contribute

- Add new entries to the tables above by filling in the relevant details.
- For papers, include the title, year, key highlights, label(s) (e.g., novel algorithms, training, learning, prompting paradigms, hardware optimization techniques), and link to the repository/paper.
- For libraries/frameworks, include the name, a short description, main highlights, label(s), and the repository URL.
- Prefer primary sources (official papers/repos) over third-party implementations when possible.
- Keep labels concise and re-use existing categories before introducing new ones.

---

## 📜 License

This project is licensed under the MIT License.
