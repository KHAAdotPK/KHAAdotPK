### KHAAdotPK (`khaa.pk`)

Welcome to **KHAAdotPK** (`khaa.pk`)! This collection of repositories is meticulously curated to provide a solid foundation for implementing various Machine Learning (ML) models using `C/C++`, `Rust` and `Zig`. The goal is to offer resources that not only enhance your understanding of the core mechanics of these models but also empower you to build robust and innovative machine learning solutions from scratch.

#### Why KHAAdotPK?

This initiative stems from the realization that we are at a pivotal moment in the evolution of AI comparable to the early stages of other transformative global phenomena. AI today is more than a technological breakthrough; it represents a societal revolution. By demystifying ML and AI implementations, the repositories at KHAAdotPK aim to dismantle the "black box" perception of these technologies, making their mechanics accessible to everyone.

Through this work, I envision a future where individuals, equipped with their own AI agents, can ethically, responsibly, and transparently harness the full potential of this technology.

#### Getting Started

To begin, simply clone the desired repository into the `./lib` directory of your project. Each repository is designed to serve as a standalone guide and resource, offering insights and code examples that reflect real world applications of machine learning principles.

#### Live Demo: Tiny CBOW in Action

A small interactive demo of the CBOW implementation (trained on just **14 lines** of abdominal pain symptoms) is available here: https://demo-mocha-delta.vercel.app/

It shows how even ultra-tiny data can yield meaningful symptom similarities — we're actively improving the UI and experience. Feedback welcome!

#### Contribute, Explore, and Innovate

Feel free to explore, experiment with, and adapt the repositories to your needs. The provided guides/articles in the repository [Machine Learning](https://github.com/KHAAdotPK/MachineLearning) are crafted to enhance your understanding and practical application of ML models. If you have any questions, suggestions, or are interested in contributing, please don't hesitate to reach out. Your feedback and collaboration are invaluable as we strive to push the boundaries of what can be achieved with ground up machine learning solutions.

Happy coding!

<small>Author, [Sohail](https://github.com/sohail).</small>

## Request for Compute Resources

The JEPA (Rust), NLP Transformer (C/C++), and Skip-Gram/CBOW projects are **100% from-scratch** implementations—no external frameworks, just custom PNG decoders, tensor ops, and even CLI arg parsers in Rust/C++/Zig (all in this repo!).

Training modest-scale models (e.g., ViT-S/16 on ImageNet-1K image subsets or a 12-layer transformer on 1M sentences) quickly outgrows a single consumer CPU.

### What I Need
| Item | Minimum Spec | Preferred |
|------|--------------|-----------|
| **GPU** | 1 × RTX 3060 / A4000 (≥8 GB VRAM) | 2 × RTX 4090 / A6000 |
| **Desktop** | 16 GB RAM, 6-core CPU | 64 GB RAM, 12-core CPU + NVMe SSD |
| **Laptop** | 16 GB RAM, integrated GPU | 32 GB RAM, RTX 4070 |

### What It Will Enable
* Full pre-training of **I-JEPA** on ImageNet-1K subsets (public dataset of 1M+ images—no libs needed).
* End-to-end training of the **C++ Transformer** for language modeling on custom corpora.
* Rapid iteration on **Skip-Gram/CBOW** with billion-token datasets.
* Open benchmarks, pretrained weights, and reproducible results for the community.

If you/your org can donate, loan, or sponsor, open an **Issue** titled **"Compute Donation"** or email **Q@khaa.pk**. Every cycle accelerates systems-level ML for all—thanks for fueling the from-scratch revolution!