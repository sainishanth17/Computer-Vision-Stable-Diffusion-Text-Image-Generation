# Text-to-image generation with Stable Diffusion
Text-to-image generator model create an image from scratch from a text description. Stable Diffusion is an open source text-to-image latent diffusion model created by the researchers and engineers from CompVis, Stability AI and LAION. It's trained on 512x512 images from a subset of the LAION-5B database. This model uses a frozen CLIP ViT-L/14 text encoder to condition the model on text prompts. With its 860M UNet and 123M text encoder, the model is relatively lightweight and runs on a GPU with at least 10GB VRAM.

The Colab notebook provided is an implementation of Stable Diffusion. It shows how to use Stable Diffusion with the Hugging Face Diffusers library.

I show some of my results testing the model in Google Colab with famous faces. These are the image inputs from left to right and from top to bottom:
- "A still of Boris Johnson in Game of Thrones"
- "Emma Watson as pirate from pirates of the caribbean"
- "A still of Mark Zuckerberg in Lord of the Rings"
- "Boris Johnson as Hulk"
- "Emma Watson as Batman"
- "A still of Mark Zuckerberg in Avatar"

![SD](https://user-images.githubusercontent.com/73080100/186401732-eacf0790-5653-442a-a8bf-f3b28cdc771f.jpg)
