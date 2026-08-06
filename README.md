# Hello, I'm Pritika 🚀

## GPU Systems Engineer | CUDA • PyTorch Distributed Training • GPU Optimization

I build and benchmark GPU workloads focused on understanding how hardware, memory, and distributed computing impact modern AI systems.

My work focuses on:

| Focus Area | Technologies |
|---|---|
| GPU Programming | CUDA, CUDA Memory Management, GPU Optimization |
| Distributed Training | PyTorch DDP, NCCL, DistributedSampler |
| Model Scaling | Tensor Parallelism, Transformer Parallelization |
| Deep Learning Systems | PyTorch, Mixed Precision Training |
| Languages | Python, C++, C |

---

# 🚀 Featured GPU Projects

<table>
<tr>
<td width="50%" valign="top">

## 🟢 GPU Graph Memory Lab

CUDA benchmarking suite analyzing how GPU memory allocation strategies impact graph analytics performance.

### Workload

- Algorithm: PageRank
- Dataset: SNAP citation graph
- Representation: CSR Graph Format
- Hardware: NVIDIA RTX 3090

### Memory Strategies Tested

| Strategy | Result |
|---|---|
| cudaMalloc | Baseline allocation |
| cudaMallocAsync | 🥇 Best runtime |
| Memory Pool | Improved reuse, higher memory usage |
| Unified Memory | Higher overhead |

### Key Finding

`cudaMallocAsync` achieved the best performance by reducing allocation overhead for repeated GPU memory operations.

🔗 [View Repository](https://github.com/Pritiks23/gpu-graph-memory-lab-)

</td>

<td width="50%" valign="top">

## 🟣 EuroSAT GPU Training Pipeline
<img width="250" alt="Screen Shot 2026-07-31 at 12 21 52 PM" src="https://github.com/user-attachments/assets/bff0c079-f320-4a77-ab86-b31f2670b388" />

End-to-end GPU accelerated computer vision training pipeline built with PyTorch.

### Implemented

✅ CUDA accelerated preprocessing  
✅ Mixed precision training (AMP)  
✅ GPU data loading optimization  
✅ Training performance analysis  
✅ Model evaluation and visualization  

### Results

| Epoch | Validation Accuracy |
|---|---:|
| Epoch 1 | 73.6% |
| Epoch 20 | **94.1%** |

### Goal

Analyze how GPU utilization, preprocessing acceleration, and training pipeline optimizations affect deep learning throughput.

🔗 [View Repository](https://github.com/Pritiks23/eurosat-hpc-training)

</td>
</tr>
</table>

<table>
<tr>
<td width="50%" valign="top">


## 🔴 GEMM Kernel Optimization Study
             <img width="527" height="300" alt="Screen Shot 2026-08-06 at 1 20 27 PM" src="https://github.com/user-attachments/assets/d46fecb4-426a-4d5c-8710-6248b68ccedb" />


CUDA benchmarking study analyzing how different matrix multiplication implementations impact GPU performance.

### Workload

- Operation: Matrix Multiplication (`C = A × B`)
- Matrix Size: `4096 x 4096`
- Precision: FP32

### GEMM Strategies Tested

| Strategy | Runtime |
| -------- | ------: |
| CPU NumPy | 221.75 ms |
| PyTorch CUDA GEMM | **2.98 ms** |
| Naive CUDA Kernel | 38.97 ms |
| Tiled CUDA Kernel | **21.18 ms** |

### Key Finding

GPU GEMM achieved **~74.5x speedup** over CPU execution.

Shared memory tiling improved custom CUDA kernel performance by **45.6%** through improved data reuse.

🔗 [View Repository](https://github.com/Pritiks23/gemm-kernel-study)

#  Distributed AI Systems

<table>
<tr>

<td width="50%">

## 🔵 PyTorch DistributedDataParallel

Multi-GPU training implementation using PyTorch distributed systems.

### Architecture

```
              Model
                |
     -------------------------
     |           |           |
   GPU 0       GPU 1       GPU 2

          NCCL AllReduce
```

### Implemented

- PyTorch DistributedDataParallel
- NCCL communication
- DistributedSampler
- Mixed precision training

### Results

- Multi-GPU RTX 3090 training
- Improved throughput through distributed execution

</td>

<td width="50%">

## 🟠 Tensor Parallel Transformer

Explored model parallelism techniques for transformer architectures.

### Architecture

```
          Transformer Layer

              Linear

        ----------------
        |              |
      GPU 0          GPU 1

     Partitioned computation
              |
        Combined output
```

### Implemented

- Tensor parallel linear layers
- Distributed model execution
- GPU workload partitioning

</td>

</tr>
</table>

---

# 🧠 GPU Engineering Focus

```
CUDA Programming
        ↓
GPU Memory Optimization
        ↓
Distributed Training
        ↓
Efficient AI Infrastructure
```

Currently exploring:

- GPU performance optimization
- CUDA-based acceleration
- Distributed deep learning systems
- Efficient AI workloads

---

# 🛠 Technical Stack

| Category | Tools |
|---|---|
| GPU Computing | CUDA, CUDA Toolkit, GPU Memory Management |
| AI Frameworks | PyTorch |
| Distributed Systems | DDP, NCCL, Tensor Parallelism |
| Programming | Python, C++, C |
| Development | Linux, Docker, Git |

---

# 📊 Engineering Highlights

| Area | Highlights |
|---|---|
| GPU Computing | CUDA memory allocation benchmarks, GPU optimization experiments |
| Distributed Training | PyTorch DDP with NCCL multi-GPU communication |
| Model Parallelism | Tensor Parallel Transformer implementation |
| Computer Vision | GPU accelerated EuroSAT training pipeline |
| Performance Engineering | Runtime analysis, memory profiling, workload benchmarking |

---

# 🧪 Current Focus


# 📫 Connect

LinkedIn: https://www.linkedin.com/in/pritika-vipin/
