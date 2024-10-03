# Stable Diffusion: Text-to-Image and Image-to-Text Generation

This repository demonstrates the use of pre-trained models from Hugging Face for both **Text-to-Image** and **Image-to-Text** generation tasks. Using Stable Diffusion for Text-to-Image generation, you can input descriptive text prompts to create high-quality images. Conversely, the Image-to-Text pipeline generates captions for images using state-of-the-art deep learning models.

The notebook is divided into two parts:
- **Text-to-Image Generation**: Generate images from textual descriptions using the Stable Diffusion model.
- **Image-to-Text Generation**: Generate textual descriptions from images using image captioning models.

The project provides an interactive experience where you can experiment with both models and customize prompts or images. Feel free to explore and play around with the notebook to create and caption your own images!

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/Raihan4520/Stable-Diffusion.git
   ```
2. Install the necessary Python libraries:
   ```bash
   pip install diffusers transformers torch accelerate pillow datasets huggingface_hub torchvision
   ```
3. Open the Jupyter Notebook `Text2Image_Image2Text_StableDiffusion.ipynb` in your preferred environment (e.g., Jupyter Notebook, Google Colab).
4. Follow the instructions inside the notebook to:
   - Generate images from text prompts.
   - Generate captions for images.
  
## Acknowledgements

This project uses the Stable Diffusion model and Hugging Face's API for both Text-to-Image and Image-to-Text tasks. Special thanks to the Hugging Face community for providing access to these powerful models.

## Contact

If you have any questions or suggestions, feel free to reach out through the repository's issues or contact me directly.
