# Image Colorization with GANs and U-Net

This project explores the application of Generative Adversarial Networks (GANs) and the U-Net architecture for the task of colorizing grayscale images. The unique feature of this approach is the use of a GAN with a generator designed to mimic the U-Net architecture, incorporating skip connections to enhance the colorization process.

## Project Overview

- **Objective**: Colorize grayscale images using a GAN with a U-Net generator.
- **Methodology**: Implement a conditional GAN with a generator that takes grayscale images as input and outputs colorized images. The discriminator assesses the authenticity of the generated images by comparing them to real color images.
- **Architecture**: The generator is inspired by the U-Net architecture, utilizing skip connections for better detail preservation and localization in the colorization process.
- **Discriminator**: A patch discriminator is used to assess the authenticity of each patch of the generated images, capturing the nuances of the colorization process.

## Getting Started

### Prerequisites

- Python 3.6+
- PyTorch 1.0+
- torchvision
- Numpy
- PIL (Python Imaging Library)

### Installation

1. Clone the repository:
git clone https://github.com/YourUsername/Image-Colorization-GAN-UNet.git

2. Navigate to the project directory:
cd Image-Colorization-GAN-UNet

3. Install the required dependencies:
pip install -r requirements.txt


### Dataset

The project utilizes a dataset of grayscale images for training. The dataset should be sufficiently large to effectively train the model. It is recommended to split the dataset into training and validation sets for model training and evaluation.

### Training the Model

To train the model, execute the training script with the appropriate dataset path and other training parameters. The script will guide you through setting up the generator and discriminator models, defining the loss functions, and training the model on your dataset.

## Results and Examples

The model should be capable of colorizing grayscale images with high realism upon successful training. The project includes examples of the model's output to showcase the quality of colorization achieved.

## Conclusion

This project demonstrates the potential of GANs, particularly when combined with the U-Net architecture, for the task of image colorization. By leveraging the strengths of both models, we can achieve high-quality, realistic colorization of grayscale images, opening up new possibilities for image processing and enhancement.

## Contributing

Contributions to this project are welcome. Please feel free to fork the repository, make changes, and submit a pull request.


