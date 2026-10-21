<p align="center">
  <img src="assets/deep-learning-compilers-banner.svg" alt="Awesome Deep Learning Compilers" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a><a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
  <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License: MIT"></a>
  <a href="https://github.com/ishandutta2007/Awesome-Deep-Learning-Compilers/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Deep-Learning-Compilers?style=flat&color=yellow" alt="GitHub Stars"></a>
  <a href="https://github.com/ishandutta2007/Awesome-Deep-Learning-Compilers/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Deep-Learning-Compilers?style=flat&color=orange" alt="GitHub Forks"></a>
  <a href="https://github.com/ishandutta2007/Awesome-Deep-Learning-Compilers/pulls"><img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg" alt="PRs Welcome"></a>
  <a href="https://github.com/ishandutta2007/Awesome-Deep-Learning-Compilers/commits/main"><img src="https://img.shields.io/github/last-commit/ishandutta2007/Awesome-Deep-Learning-Compilers" alt="Last Commit"></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

# 🚀 Awesome-Deep-Learning-Compilers

> **The definitive directory of Deep Learning Compilers, Kernel Optimization DSLs, and High-Throughput Inference Engines for AI & Machine Learning Engineers.**

A carefully curated, community-maintained index of enterprise **SaaS optimization platforms** and cutting-edge **open-source deep learning compilers**. Designed for machine learning systems researchers, MLOps practitioners, and inference platform engineers building ultra-low-latency, hardware-accelerated AI infrastructure across GPUs, CPUs, TPUs, NPUs, and FPGAs.

### 🔍 Quick Search & Hardware Taxonomy

| Hardware Target / Acceleration Stack | Leading Open-Source Compilers & Runtimes | Enterprise & Cloud Solutions |
| :--- | :--- | :--- |
| **NVIDIA GPUs** (Blackwell, Hopper, Ada, Ampere) | [TensorRT](https://github.com/NVIDIA/TensorRT), [TensorRT-LLM](https://github.com/NVIDIA/TensorRT-LLM), [PyTorch Inductor](https://github.com/pytorch/pytorch), [OpenAI Triton](https://github.com/triton-lang/triton), [vLLM](https://github.com/vllm-project/vllm), [SGLang](https://github.com/sgl-project/sglang) | [NVIDIA AI Enterprise](https://www.nvidia.com/en-us/data-center/products/ai-enterprise/), [Modular MAX](https://www.modular.com/max) |
| **Apple Silicon** (M1–M4 Neural Engine, Metal GPU) | [llama.cpp](https://github.com/ggerganov/llama.cpp), [Apache TVM](https://github.com/apache/tvm), [ONNX Runtime](https://github.com/microsoft/onnxruntime), [Taichi](https://github.com/taichi-dev/taichi) | [Apple Core ML](https://developer.apple.com/documentation/coreml) |
| **Intel Architectures** (Xeon CPUs, Arc GPUs, Gaudi, NPU) | [Intel OpenVINO](https://github.com/openvinotoolkit/openvino), [ONNX Runtime](https://github.com/microsoft/onnxruntime), [oneDNN / PyTorch](https://github.com/pytorch/pytorch) | Intel Tiber Developer Cloud |
| **AMD Platforms** (ROCm GPUs, Instinct, Xilinx FPGAs) | [Vitis AI](https://github.com/Xilinx/Vitis-AI), [vLLM ROCm](https://github.com/vllm-project/vllm), [IREE](https://github.com/iree-org/iree), [Apache TVM](https://github.com/apache/tvm) | AMD ROCm Enterprise Solutions |
| **Mobile & Embedded** (ARM NEON, Hexagon DSP, Vulkan) | [ncnn](https://github.com/Tencent/ncnn), [MNN](https://github.com/alibaba/MNN), [TNN](https://github.com/Tencent/TNN), [microTVM](https://github.com/apache/tvm) | [Qualcomm AI Hub](https://aihub.qualcomm.com/) |
| **Custom ASICs & Cloud Accelerators** (TPU, Inferentia) | [OpenXLA](https://github.com/openxla/xla), [IREE](https://github.com/iree-org/iree), [BladeDISC](https://github.com/alibaba/BladeDISC) | [AWS Neuron](https://aws.amazon.com/machine-learning/neuron/) |


## 📑 Table of Contents

- [🔍 Quick Search & Hardware Taxonomy](#-quick-search--hardware-taxonomy)
- [🌐 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [🏢 SaaS & Enterprise Hosted Platforms](#-saas--enterprise-hosted-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⚖️ Disclaimer & Engineering Trade-Offs](#️-disclaimer--engineering-trade-offs)
- [⭐ Star History](#-star-history)



## 🌐 Sector Overview & Market Dynamics

The global AI compiler and kernel optimization market is estimated at **$310M–$330M in 2026** (projected to reach over **$4.0B by 2035 at a 32.1% CAGR** as part of the broader $175B+ AI acceleration & inference infrastructure market). The sector is **highly concentrated and winner-take-most** among silicon hyperscalers and GPU giants (NVIDIA, Apple, Amazon AWS, and Qualcomm) who tightly couple proprietary compilers to their hardware to maintain platform moats, while an innovative tier of independent compiler platforms (such as Modular MAX) and open intermediate standards (MLIR, TVM, Triton) actively compete to unify and desegregate cross-hardware deployment.

## 🏢 SaaS & Enterprise Hosted Platforms

| 🛠️ Platform / Tool | 🏢 Provider & Company Size (Valuation / Revenue) | 🎯 Focus & Hardware Targets | 💰 Pricing (Starting Tier) | 🎁 Free Tier / Free Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| [**Apple Core ML**](https://developer.apple.com/documentation/coreml) | **Apple Inc.**<br>• Valuation: ~$3.5 Trillion Market Cap<br>• Revenue: $391.0B (FY24) | On-device inference compiler & execution engine targeting Apple Silicon (Apple Neural Engine, Metal GPU, CPU) across iOS, iPadOS, macOS, and visionOS. | **$99/year** (Apple Developer Program membership for device provisioning, TestFlight, and App Store distribution). | **Free forever** local personal device provisioning via Xcode (deploy to up to 3 personal devices with 7-day provisioning certificate renewal; App Store deployment excluded). |
| [**NVIDIA AI Enterprise (TensorRT Support)**](https://www.nvidia.com/en-us/data-center/products/ai-enterprise/) | **NVIDIA Corporation**<br>• Valuation: ~$3.3 Trillion Market Cap<br>• Revenue: $96.3B (FY24) | Enterprise deep learning compiler and inference runtime with production SLA, continuous kernel autotuning, certified NGC containers, and TensorRT-LLM support. | **$4,500/GPU/year** (Standard enterprise software license) or **$1.00/GPU-hour** on cloud marketplaces (AWS, Azure, GCP). | **90-day free trial** evaluation license via NVIDIA NGC (full access to NVIDIA AI Enterprise software stack, TensorRT containers, and enterprise documentation). |
| [**AWS Neuron**](https://aws.amazon.com/machine-learning/neuron/) | **Amazon.com, Inc. (AWS)**<br>• Valuation: ~$2.1 Trillion Market Cap<br>• Revenue: $574.8B (FY24) | Cloud compiler & runtime SDK tailored for AWS Inferentia (Inf1/Inf2) and Trainium (Trn1/Trn2) custom AI accelerators. Integrates with PyTorch and vLLM. | **$0.758/hour** (On-demand `inf2.xlarge` instance in us-east-1 with 1 Inferentia2 chip, 4 vCPUs, 16 GiB memory). | **12-month AWS Free Tier** (750 hrs/mo `t2.micro`/`t3.micro`); 0 free accelerator hours on Inf2, but eligible for **$300 proof-of-concept credits** via AWS Free Credit programs (valid 90 days). |
| [**Qualcomm AI Hub (SNPE / QNN)**](https://aihub.qualcomm.com/) | **Qualcomm Incorporated**<br>• Valuation: ~$190 Billion Market Cap<br>• Revenue: $38.9B (FY24) | Cloud-hosted compiler, quantizer, and profiling platform to deploy and benchmark optimized models on physical Snapdragon mobile/edge silicon and NPU/Hexagon DSPs. | **$0.00** (Community Access); Enterprise dedicated hardware fleet testing and private bench farm starts at **$2,000/month**. | **Free forever** community access with up to 5 concurrent queued device profiling and compilation jobs across hosted Snapdragon devices (8 Gen 2/3/4, X Elite) and unlimited format conversions. |
| [**Modular MAX Platform**](https://www.modular.com/max) | **Modular Inc.**<br>• Valuation: ~$600 Million<br>• Series A Funding | Unified AI compiler framework and execution runtime (built on Mojo) delivering cross-hardware inference acceleration across heterogeneous CPUs and GPUs. | **$0.00** (MAX Developer Edition); Cloud endpoints start at **$0.05 / 1M input tokens** and **$0.15 / 1M output tokens**; BYOC enterprise starts at **$5,000/month**. | **Free forever** MAX Developer Edition for local workstation/single-machine usage with full Mojo compiler access and containers under 1GB footprint. |

## 💻 Open-Source GitHub Projects

Curated open-source deep learning compilers, kernel optimization DSLs, inference runtimes, and high-performance execution engines—sorted in descending order of GitHub community stars.

- [**llama.cpp**](https://github.com/ggerganov/llama.cpp) [![GitHub stars](https://img.shields.io/github/stars/ggerganov/llama.cpp?style=social&color=white)](https://github.com/ggerganov/llama.cpp/stargazers)
  **Port of Facebook's LLaMA model in pure C/C++** (MIT). **The reference standard for quantized CPU and edge inference**. Features zero-dependency C/C++ architecture, state-of-the-art k-quants (2-bit to 8-bit integer quantization), and hardware acceleration across Apple Metal, ARM NEON, AVX-512, CUDA, and SYCL. **Best for**: on-device, local edge, and CPU-optimized LLM execution.

- [**PyTorch (torch.compile / Inductor / TorchDynamo)**](https://github.com/pytorch/pytorch) [![GitHub stars](https://img.shields.io/github/stars/pytorch/pytorch?style=social&color=white)](https://github.com/pytorch/pytorch/stargazers)
  **Tensors and Dynamic neural networks in Python with strong GPU acceleration** (BSD-3-Clause). Introduces **`torch.compile`**, powered by **TorchDynamo** for Python frame capture, **AOTAutograd** for ahead-of-time graph tracing, and **TorchInductor** as the deep learning compiler generating optimized OpenAI Triton and C++ kernels. **Best for**: transparent out-of-the-box PyTorch training and inference compilation with zero code refactoring.

- [**vLLM**](https://github.com/vllm-project/vllm) [![GitHub stars](https://img.shields.io/github/stars/vllm-project/vllm?style=social&color=white)](https://github.com/vllm-project/vllm/stargazers)
  **A high-throughput and memory-efficient inference and serving engine for LLMs** (Apache-2.0). **The production gold standard for enterprise LLM serving**. Pioneers **PagedAttention** for near-zero memory waste in KV caching, continuous batching, chunked prefill, and native OpenAI-compatible API serving. Integrates with FlashAttention, FlashInfer, and custom Triton kernels. **Best for**: high-concurrency LLM and vision-language model serving on NVIDIA, AMD ROCm, and AWS Neuron GPUs.

- [**SGLang**](https://github.com/sgl-project/sglang) [![GitHub stars](https://img.shields.io/github/stars/sgl-project/sglang?style=social&color=white)](https://github.com/sgl-project/sglang/stargazers)
  **SGLang is a fast serving framework for large language models and vision language models** (Apache-2.0). Features **RadixAttention** for automatic KV cache reuse across multi-turn chats and shared prefixes, structured speculative decoding, and optimized execution pipelines. **Best for**: complex reasoning workflows, structured JSON generation, agentic multi-turn conversations, and ultra-high token throughput.

- [**Taichi**](https://github.com/taichi-dev/taichi) [![GitHub stars](https://img.shields.io/github/stars/taichi-dev/taichi?style=social&color=white)](https://github.com/taichi-dev/taichi/stargazers)
  **Productive & portable high-performance programming language for machine learning and graphics** (Apache-2.0). A high-performance domain-specific compiler embedded in Python that compiles imperative tensor operations directly to CUDA, Metal, Vulkan, and CPU vector instructions. **Best for**: custom differentiable physics, sparse neural networks, and high-performance kernel compilation.

- [**ncnn**](https://github.com/Tencent/ncnn) [![GitHub stars](https://img.shields.io/github/stars/Tencent/ncnn?style=social&color=white)](https://github.com/Tencent/ncnn/stargazers)
  **High-performance neural network inference computing framework optimized for mobile platforms** (BSD-3-Clause). Developed by Tencent, ncnn is written in pure C++ with zero external dependencies, featuring extreme ARM NEON assembly optimizations, multi-core parallel scheduling, and Vulkan GPU acceleration. **Best for**: ultra-lightweight mobile applications, embedded IoT microcontrollers, and real-time vision on consumer hardware.

- [**ONNX Runtime**](https://github.com/microsoft/onnxruntime) [![GitHub stars](https://img.shields.io/github/stars/microsoft/onnxruntime?style=social&color=white)](https://github.com/microsoft/onnxruntime/stargazers)
  **Cross-platform, high-performance ML inferencing and training accelerator** (MIT). **The most widely deployed enterprise inference runtime**. Supports unified execution providers (EPs) including NVIDIA TensorRT, Intel OpenVINO, AMD ROCm, Qualcomm QNN, DirectML, and Apple Core ML. Powering production Microsoft services like Bing, Microsoft 365, and Azure AI. **Best for**: cross-platform portability without vendor lock-in.

- [**OpenAI Triton**](https://github.com/triton-lang/triton) [![GitHub stars](https://img.shields.io/github/stars/triton-lang/triton?style=social&color=white)](https://github.com/triton-lang/triton/stargazers)
  **Development environment for parallel programming and custom GPU kernel compilation** (MIT). A Python-based language and compiler that enables developers with no CUDA experience to write highly efficient GPU kernels that match or exceed vendor libraries. Backed by OpenAI, Meta, and Microsoft, and used as the primary backend compiler for PyTorch Inductor. **Best for**: writing custom fused attention, GEMM, and normalization kernels.

- [**MNN (Alibaba)**](https://github.com/alibaba/MNN) [![GitHub stars](https://img.shields.io/github/stars/alibaba/MNN?style=social&color=white)](https://github.com/alibaba/MNN/stargazers)
  **Blazing-fast, lightweight deep learning inference engine and compiler** (Apache-2.0). Alibaba's flagship mobile inference framework, heavily battle-tested on the Taobao app across hundreds of millions of daily active devices. Features comprehensive graph optimization, geometric computing, and hardware acceleration on ARM, OpenCL, and Vulkan. **Best for**: mobile and embedded client-side deep learning inference.

- [**TensorRT-LLM**](https://github.com/NVIDIA/TensorRT-LLM) [![GitHub stars](https://img.shields.io/github/stars/NVIDIA/TensorRT-LLM?style=social&color=white)](https://github.com/NVIDIA/TensorRT-LLM/stargazers)
  **NVIDIA TensorRT-LLM provides users with an easy-to-use Python API to compile and run large language models** (Apache-2.0). Employs state-of-the-art kernel fusion, FP8/FP4 quantization, in-flight batching, and tensor parallelism across NVIDIA Hopper, Ada Lovelace, and Blackwell GPUs. **Best for**: extracting the absolute maximum LLM throughput and lowest latency from NVIDIA GPU infrastructure.

- [**Apache TVM**](https://github.com/apache/tvm) [![GitHub stars](https://img.shields.io/github/stars/apache/tvm?style=social&color=white)](https://github.com/apache/tvm/stargazers)
  **Open Machine Learning Compiler Framework for CPUs, GPUs, and Machine Learning Accelerators** (Apache-2.0). **The foundational open-source deep learning compiler framework**. Employs a cross-level compiler architecture combining **TensorIR** for tensor program optimization and **Relax** for graph-level transformations. Compiles models to minimal standalone executables across CUDA, ROCm, Vulkan, Metal, OpenCL, and microcontrollers via microTVM. **Best for**: teams seeking an open, vendor-neutral, hackable compilation stack spanning edge to datacenter.

- [**NVIDIA TensorRT (Open-Source Components)**](https://github.com/NVIDIA/TensorRT) [![GitHub stars](https://img.shields.io/github/stars/NVIDIA/TensorRT?style=social&color=white)](https://github.com/NVIDIA/TensorRT/stargazers)
  **NVIDIA TensorRT is an SDK for high-performance deep learning inference** (Apache-2.0 for open-source components). Houses open-source parsers (ONNX parser), custom plugins, sample applications, and PyTorch bindings (Torch-TensorRT) that accompany the proprietary TensorRT core compilation engine. **Best for**: developers targeting peak inference latency on NVIDIA GPUs with custom plugin requirements.

- [**Triton Inference Server**](https://github.com/triton-inference-server/server) [![GitHub stars](https://img.shields.io/github/stars/triton-inference-server/server?style=social&color=white)](https://github.com/triton-inference-server/server/stargazers)
  **Enterprise multi-framework inference serving solution optimized for CPUs and GPUs** (BSD-3-Clause). Provides production HTTP/REST and gRPC endpoints, dynamic batching, concurrent model execution, model pipelining (Ensemble), and model metrics. Seamlessly orchestrates backends including TensorRT, ONNX Runtime, OpenVINO, PyTorch, and vLLM. **Best for**: unified production serving architecture across mixed hardware fleets.

- [**Intel OpenVINO**](https://github.com/openvinotoolkit/openvino) [![GitHub stars](https://img.shields.io/github/stars/openvinotoolkit/openvino?style=social&color=white)](https://github.com/openvinotoolkit/openvino/stargazers)
  **Open-source toolkit for optimizing and deploying deep learning models on Intel architectures** (Apache-2.0). Maximizes throughput across Intel CPUs (AVX2/AVX-512/AMX), integrated GPUs, discrete Intel Arc GPUs, and Intel NPUs. Features advanced graph compilation, automatic INT8/INT4 quantization with NNCF, and optimized GenAI pipelines. **Best for**: edge and enterprise deployments committed to Intel silicon.

- [**TNN (Tencent)**](https://github.com/Tencent/TNN) [![GitHub stars](https://img.shields.io/github/stars/Tencent/TNN?style=social&color=white)](https://github.com/Tencent/TNN/stargazers)
  **Uniform deep learning inference framework customized for mobile devices** (BSD-3-Clause). Features cross-platform acceleration targeting Android, iOS, Linux, and Windows, with high-performance kernel tuning for ARM CPU, Mali GPU, Adreno GPU, and Apple Metal. **Best for**: consumer mobile deployments requiring cross-platform compatibility.

- [**OpenXLA (XLA)**](https://github.com/openxla/xla) [![GitHub stars](https://img.shields.io/github/stars/openxla/xla?style=social&color=white)](https://github.com/openxla/xla/stargazers)
  **Accelerated Linear Algebra (XLA) compiler for deep learning and machine learning** (Apache-2.0). An open-source domain-specific compiler for linear algebra that accelerates models in JAX, TensorFlow, and PyTorch (via PyTorch/XLA). Powers Google Cloud TPU infrastructure and delivers automated operator fusion and memory allocation across GPUs and TPUs. **Best for**: JAX workloads, large-scale TPU training/inference clusters, and custom ASIC hardware targets.

- [**IREE**](https://github.com/iree-org/iree) [![GitHub stars](https://img.shields.io/github/stars/iree-org/iree?style=social&color=white)](https://github.com/iree-org/iree/stargazers)
  **Intermediate Representation Execution Environment: Retargetable MLIR-based compiler and runtime** (Apache-2.0). Built entirely upon LLVM/MLIR, IREE lowers high-level machine learning models (from PyTorch, JAX, TFLite, and ONNX) into unified hardware-specific binaries for Vulkan, SPIR-V, Metal, CUDA, ROCm, and CPU SIMD. **Best for**: hardware vendors building compiler backends and teams desiring retargetable compilation.

- [**Vitis AI (AMD/Xilinx)**](https://github.com/Xilinx/Vitis-AI) [![GitHub stars](https://img.shields.io/github/stars/Xilinx/Vitis-AI?style=social&color=white)](https://github.com/Xilinx/Vitis-AI/stargazers)
  **Integrated Development Environment for AI inference acceleration on AMD adaptive platforms** (Apache-2.0). Provides model quantizers, graph optimizers, and Deep Learning Processor Unit (DPU) overlays tailored for AMD adaptable SoCs, Versal AI engines, and Alveo Data Center accelerator cards. **Best for**: FPGA-based embedded vision, industrial IoT, and real-time deterministic inference.

- [**BladeDISC (Alibaba)**](https://github.com/alibaba/BladeDISC) [![GitHub stars](https://img.shields.io/github/stars/alibaba/BladeDISC?style=social&color=white)](https://github.com/alibaba/BladeDISC/stargazers)
  **End-to-end DynamIc Shape Compiler for machine learning workloads** (Apache-2.0). An MLIR-based dynamic shape deep learning compiler supporting both TensorFlow and PyTorch frontends, optimized for GPUs and x86 CPUs with dynamic input dimensions and runtime shape variation. **Best for**: e-commerce and search workloads where dynamic sequence lengths cause overhead in static compilers.


## 🤝 How to Contribute

We welcome contributions from ML engineers, systems researchers, and hardware architects!

1. 🍴 **Fork the repository** on GitHub.
2. 📝 **Add or edit entries** in [`README.md`](README.md) adhering to existing table/list formatting.
3. 🔗 **Include clear details**: project name, official documentation/repo link, star badge, and target silicon backends.
4. 🚀 **Submit a Pull Request** with a succinct description of your addition.

⭐ **Star the repo** if you find it useful for your production AI stack!

## ⚖️ Disclaimer & Engineering Trade-Offs

- 🔍 **Community-Curated Directory**: This guide is maintained by the AI systems community—not an official endorsement of any vendor or framework.
- 📐 **Evaluation Criteria**: Deep learning compilers must be critically assessed for **hardware target coverage**, **dynamic shape support**, **quantization accuracy**, and **licensing** (open Apache-2.0/MIT vs. proprietary vendor runtimes).
- 🧩 **Compiler vs. Runtime vs. Serving Layer**:
  - ⚙️ **Compilers** (*Apache TVM, TensorRT, OpenVINO, OpenXLA, IREE*): Transform computational graphs and kernel IRs into hardware-optimized machine code.
  - 🏎️ **Runtimes & Execution Engines** (*ONNX Runtime, vLLM, SGLang, llama.cpp*): Manage KV cache allocations, execution scheduling, and low-precision inference loops.
  - 🌐 **Serving Orchestrators** (*Triton Inference Server*): Expose HTTP/gRPC APIs, handle dynamic micro-batching, and manage multi-model routing across server fleets.
- 🔄 **Portability vs. Peak Speed**: Fully vendor-neutral compilers hedge against GPU supply constraints, whereas vendor-native compilers unlock peak single-chip FLOPS.
- 🧪 **Numerical Validation**: Aggressive graph transformations, operator fusions, and low-bit quantization (FP8, INT4, NF4) can introduce numerical drift—always validate accuracy against uncompiled reference models before production deployment.



---



**Made for ML engineers, platform teams, and organizations building transparent inference solutions.**  

Let's make Deep Learning Compilers more open, data-driven, and hardware-aware.

##  Star History
[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Deep-Learning-Compilers&type=date&legen==top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Deep-Learning-Compilers&type=date&legend=top-left)
