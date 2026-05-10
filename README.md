# bdh
Baby Dragon Hatchling neural model 01

# PsycorAI: Autonomous Edge Intelligence

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)[![Python 3.10+](https://img.shields.io/badge/python-3.10+-blue.svg)](https://www.python.org/downloads/)
[![Hardware: NVIDIA RTX](https://img.shields.io/badge/Hardware-NVIDIA_RTX_5080/3080-green.svg)](https://www.nvidia.com/en-us/geforce/graphics-cards/50-series/)

PsycorAI™ is a research-driven venture focused on biologically-inspired neural architectures for decentralized environments. Our first project is focused on the development of **PsycorEdge™**, a 1.1B parameter Baby Dragon Hatchling (BDH) model optimized for local inference.

---

## Technical Overview

The PsycorEdge architecture departs from standard Transformer-based attention by implementing a scale-free network topology. This approach mimics micro-level biological neuron interactions to achieve higher reasoning density with a lower parameter footprint.

### Key Characteristics

* **Architecture:** Baby Dragon Hatchling (BDH)
* **Optimization:** INT8/FP16 quantization for local VRAM efficiency
* **Target Throughput:** Sub-100ms token latency on consumer-grade NVIDIA hardware
* **Framework:** Native compatibility with OpenClaw agentic supervisors

## Compelling Features

* **Neural Plasticity:** (Continuous Learning): Unlike Transformer models that are "frozen" post-training, PsycorEdge utilizes synaptic plasticity. Through Hebbian-inspired learning, the model adapts during inference—strengthening or weakening connections based on real-world interaction. This allows the model to internalize new patterns without requiring a full retraining cycle.

* **Graph-Native Memory:** In BDH architectures, memory is not a transient external cache (like a KV cache); it is "baked" into the neural graph itself. By storing state within the synaptic tension of the network, PsycorEdge solves the "Groundhog Day" effect of traditional LLMs, allowing for durable, long-term knowledge retention that evolves with the user.

* **Scale-Free Topology (Emergent Reasoning):** PsycorEdge is built on a scale-free network of locally interacting "neuron particles." This mimicry of biological brain connectivity allows for sparse activations—where only ~5% of the model fires at any given time—resulting in high-density reasoning and superior performance on complex, non-linguistic tasks (e.g., the Sudoku Extreme benchmark) that typically stump standard Transformers.

## Hardware Requirements

To achieve optimal inference speeds, the following specifications are recommended:
* **GPU:** NVIDIA GeForce RTX 3080 or 5080 (10GB+ VRAM)
* **OS:** Windows 11 / Linux (Ubuntu 22.04+)
* **Drivers:** CUDA 12.x or later

## Project Status

1. **Phase I (Current):** Research & Optimization – Finalizing BDH architecture and local hardware offloading (NVIDIA RTX 5080/3080).

2. **Phase II:** "Psycor-Lite" Preview (500M) – Release of a smaller, functional 500M model via Web UI for community stress-testing and feedback.

3. **Phase III:** The Flagship (1.1B) – Development and private internal testing of the full-scale PsycorEdge model.

4. **Phase IV:** Commercial Beta (Web UI) – Launch of the Web UI and API access for the 1.1B model. This is where you establish your product-market fit and commercial stability.

5. **Phase V:** Full Weight Release (Open Core) – Public release of the 1.1B weights under an open-source license once the commercial ecosystem (Phase IV) is self-sustaining.

**Note:** We are committed to an Open Core future. Weights for the 1.1B model will be released following the stabilization of our commercial Web UI.

## Intellectual Property & Licensing

**Psycor.ai™** and **PsycorEdge™** are trademarks of Psycor.ai, established May 2026. All rights reserved.

The source code and model weights in this repository are licensed under the **Apache License 2.0**. Use of these materials is subject to the terms and conditions outlined in the [LICENSE](./LICENSE) file. 

For commercial inquiries or specialized licensing regarding the BDH architecture, please contact the PsycorAI team at Psycor.ai -- coming soon.
