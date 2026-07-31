# Hi, I'm Pritika 👋

GPU Systems Engineer focused on CUDA, distributed training, and AI infrastructure.

I build and benchmark GPU workloads with a focus on:
- CUDA memory optimization
- Multi-GPU training
- Distributed deep learning
- GPU performance analysis

Currently exploring how GPU systems design impacts the efficiency and scalability of modern AI workloads.

---

## 🚀 Featured Projects

### 🟢 GPU Graph Memory Lab

A CUDA benchmarking suite exploring how GPU memory allocation strategies impact graph analytics performance.

**Workload:**
- PageRank on SNAP citation graph
- CSR graph representation
- CUDA kernels
- NVIDIA RTX 3090 benchmarking

**Compared:**
- `cudaMalloc`
- `cudaMallocAsync`
- Custom GPU Memory Pool
- Unified Memory

**Key Finding:**
- `cudaMallocAsync` achieved the best runtime
- Improved performance by reducing allocation overhead

🔗 [gpu-graph-memory-lab](https://github.com/Pritiks23/gpu-graph-memory-lab)

---

### 🟣 EuroSAT GPU Training Pipeline

End-to-end GPU accelerated image classification training pipeline using PyTorch.

Implemented:
- CUDA accelerated preprocessing
- Mixed precision training
- GPU data loading optimization
- Training benchmarking

Built to analyze how input pipelines and GPU utilization affect deep learning performance.

🔗 [eurosat-hpc-training](https://github.com/Pritiks23/eurosat-hpc-training)

---

### 🔵 Distributed Data Parallel Training

Multi-GPU training implementation using PyTorch DistributedDataParallel.

Technologies:
- PyTorch DDP
- NCCL communication
- DistributedSampler
- Mixed precision training

Results:
- Multi-GPU RTX 3090 training
- Improved throughput through distributed execution

---

### 🟠 Tensor Parallel Transformer

Implemented tensor parallelism concepts for transformer architectures.

Explored:
- Splitting model computation across GPUs
- Parallel linear layers
- Distributed model execution

---

## 🛠 Technical Focus

### GPU Computing
CUDA • CUDA Memory Management • GPU Optimization • GPU Profiling

### Deep Learning Systems
PyTorch • DistributedDataParallel • Tensor Parallelism • Mixed Precision Training

### Programming
Python • C++ • C • Linux

### Tools
Docker • Git • NVIDIA CUDA Toolkit

---

## 📈 Current Interests

- GPU performance optimization
- Distributed AI systems
- Efficient deep learning infrastructure
- CUDA programming

---

## 📫 Connect

LinkedIn: https://www.linkedin.com/in/pritika-vipin/
