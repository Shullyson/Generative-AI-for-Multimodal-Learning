# Multimodal Generative Model

## Overview
This project focuses on integrating multimodal inputs (text and images) into generative models for advanced text and image generation tasks. The goal is to create a system that can accept both image and text inputs, process them using a generative model, and produce coherent and context-aware outputs.

## Features
- Accepts both image and text inputs
- Utilizes a generative model for producing text and image outputs
- Context-aware processing for better coherence
- Scalable and modular architecture for easy extension

## Installation
```bash
# Clone the repository
git clone https://github.com/Shullyson/Generative-Ai-Multimodal-Learning.git
cd Generative-Ai-Multimodal-Learning

# Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt
```

## Usage
```python
from model import MultimodalGenerator

generator = MultimodalGenerator()
result = generator.generate(text="A cat sitting on a bench", image="path/to/image.jpg")
print(result)
```

## Model Architecture
- **Text Encoder**: Processes text input and extracts meaningful features
- **Image Encoder**: Converts image input into a latent representation
- **Fusion Module**: Merges both modalities for context-aware generation
- **Decoder**: Generates output based on the fused representation




