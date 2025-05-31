# Text-to-Image Generation

This project focuses on generating realistic images from natural language text prompts using deep learning and diffusion models. It is part of a PRAD Lab initiative aimed at exploring generative AI and multimodal learning systems.

The core objective is to translate textual descriptions into visually coherent images using state-of-the-art techniques in NLP and computer vision.

---

## Objectives

- Build a pipeline that accepts natural language text and returns synthesized images.
- Integrate pre-trained diffusion models (e.g., Stable Diffusion) for realistic image generation.
- Study and experiment with prompt engineering, aspect ratio control, and generation latency.

---

## Key Features

- **Text Prompt Handling**: Processes user input for compatibility with diffusion pipelines.
- **Stable Diffusion Integration**: Utilizes Hugging Face Diffusers for model access and image generation.
- **Aspect Ratio Customization**: Allows generation of images with varying dimensions.
- **Latency Analysis**: Measures and compares time taken for generation across different configurations.
- **Metadata-Driven Generation**: Automates image production based on structured prompt data.

---

## Experiments Conducted

- Aspect ratio vs. quality trade-off
- Latency benchmarks across prompt lengths
- Consistency and randomness in generation

---

## Tech Stack

- Python
- Hugging Face `diffusers`, `transformers`
- PyTorch
- PIL, matplotlib
- Jupyter Notebook

---

## Example Output

> Text Prompt: *"A futuristic cityscape at sunset with flying cars."*  
> Generated Image: *(shown inline or saved to output folder)*

---

## Future Work

- Add support for ControlNet for fine-grained image conditioning
- Enable GUI or web app interface for user-friendly access
- Experiment with attention heatmaps to interpret model focus

