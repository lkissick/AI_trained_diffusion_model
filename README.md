# AI Trained Diffusion Model
Code for a diffusion model that learns from a dataset of AI-generated images.

Included in this repository is a Python script for a UNet (credit goes to MaximeVandegar for creating this--I only changed the channel structure to allow for RGB images rather than greyscale), a jupyter notebook compatible for Google Colab that trains the model, and results after training for 200,000 steps.

Here is the link to the data used: https://www.kaggle.com/datasets/superpotato9/dalle-recognition-dataset

To use these files, upload the zipped data to your Drive, upload the unet file to your working Colab session, and run the notebook from there.

The purpose of this project is to explore which features emerge from a diffusion model that is trained on AI-generated images.
