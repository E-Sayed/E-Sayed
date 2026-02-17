# Ehsan Sayed

R&D engineer in manufacturing, building open source software solutions for industrial environments.

## Projects

### [MuDeNet-PyTorch](https://github.com/E-Sayed/mudenet-pytorch)
A PyTorch implementation of MuDeNet — a teacher-student anomaly detection framework that uses multi-scale patch descriptors to spot defects in images. A distilled teacher generates dense feature embeddings; lightweight student networks learn to reconstruct them, and anything they can't reconstruct gets flagged as anomalous. Two branches (structural and logical) let it catch both local defects like scratches and global issues like missing components.

Targets industrial inspection across MVTec AD, MVTec LOCO, and VisA (32 categories total).

**Stack:** Python · PyTorch · torchvision · scikit-learn

### [Edge Inference Service](https://github.com/E-Sayed/edge-inference-service)
A model-agnostic image classification API built for edge deployment. Upload an image, get predictions back with confidence scores and a full timing breakdown. Swap in any ONNX classification model via configuration — no code changes needed.

The included example classifies manufacturing defects on hot-rolled steel strips using a fine-tuned MobileNet v2.

**Stack:** Python · FastAPI · ONNX Runtime · Docker

## In Progress

### OCR
A self-hosted OCR web application that extracts text, tables, and figures from images using a local vision-language model.

Runs GLM-OCR (0.9B parameters) via Ollama — no API keys, no cloud dependencies, fully offline-capable.

**Stack:** Python · FastAPI · Ollama · Docker Compose · Pico CSS

### Production Monitor
An OEE dashboard for manufacturing. Shows management how well machines are running, what causes downtime, and enables analysis on production improvements.

**Stack:** C# · .NET · React · PostgreSQL
