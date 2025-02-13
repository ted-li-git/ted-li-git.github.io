# deepseek简介
众所周知，deepseek作为在年前出品的ai智能助手，以好用，成本低，迅速冲上了热搜，当然这样也会导致用户多，服务器忙不过来，所以用deepseek时服务器繁忙，回答慢都是家常便饭，但本地部署可以极大的优化这一问题（具体性能还是看什么版本，比如1.5b、7b、8b、14b这些版本）

# 部署
## 准备工作
硬件要求参考下文：
1. GPU 需求
推荐 GPU：
NVIDIA Tesla T4（16GB VRAM）
NVIDIA RTX 3090（24GB VRAM）
NVIDIA A100（40GB/80GB VRAM）
最低 GPU：
NVIDIA GTX 1080 Ti（11GB VRAM）或 RTX 2080 Ti（11GB VRAM）
显存要求：
1.5B 模型在 FP16 精度下需要约 3-4GB 显存。
如果使用量化技术（如 INT8），显存需求可进一步降低。
2. CPU 需求
推荐 CPU：
多核高性能 CPU（如 Intel Xeon 或 AMD Ryzen 9）。
最低 CPU：
4 核以上，支持 AVX2 指令集。
3. 内存（RAM）需求
推荐内存：
16GB 或以上。
最低内存：
8GB（仅适用于轻量推理）。
4. 存储需求
模型大小：
FP16 精度下约 3GB。
INT8 量化后约 1.5GB。
推荐存储：
SSD（至少 10GB 空闲空间，用于加载模型和缓存）。
5. 软件环境
框架：
PyTorch、TensorFlow 或 ONNX Runtime。
CUDA 版本：
推荐 CUDA 11.x 或以上。

## 必要框架
需要ollama，ollama官网：ollama.com

## 开始正式部署
打开Windows power shell定位到system32文件夹（一般都在这）输入`ollama run deepseek-r1:1.5b`稍等片刻就大功告成