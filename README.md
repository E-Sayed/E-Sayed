# Ehsan Sayed

R&D engineer in manufacturing, building open source software solutions for industrial environments.

## Projects

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
