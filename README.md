Demo
Loom video:
https://www.loom.com/share/318a7f10027c4c54b1e52f0bbe984f65

Installation
pip install opencv-python-headless sentence-transformers transformers accelerate qwen-vl-utils torch

Method

Temporal Segmentation

Used CLIP for extracting visual embeddings

Used cosine similarity between consecutive frames

Drops in similarity are treated as temporal boundaries

Annotation

Used Qwen-2.5-VL-3B for generating segment-level descriptions
