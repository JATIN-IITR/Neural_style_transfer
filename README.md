# Neural Style Transfer

This project demonstrates Neural Style Transfer (NST) using PyTorch, where the style of one image is applied to the content of another image. The implementation leverages a pre-trained ResNet50 model for feature extraction and optimization techniques to achieve stylized images.

## Setup

To run this project, ensure you have installed the following dependencies:

- `torch`
- `torchvision`

You can install them using pip:
pip install torch torchvision


## Getting Started

1. Mount Google Drive to access your content and style images stored there.
2. Preprocess images for compatibility with the NST model.
3. Extract features from content and style images using a pre-trained ResNet50 model.
4. Calculate style loss and content loss to optimize a target image.
5. Use gradient descent optimization to minimize the total loss function.
6. Visualize the final stylized image and compare it with the original content image.

## Implementation Details

- **Model**: Utilizes a pre-trained ResNet50 model for feature extraction.
- **Loss Calculation**: Computes content loss and style loss based on feature maps and Gram matrices.
- **Optimization**: Uses AdamW optimizer to minimize the total loss function.
- **Visualization**: Displays the original content image, style image, and the resulting stylized image.

## Usage

1. **Set Up Environment**: Install necessary packages and mount Google Drive.
2. **Load Images**: Define paths to your content and style images in Google Drive.
3. **Run NST Process**: Execute the Neural Style Transfer process using the defined functions.
4. **Visualize Results**: View the original content image, style image, and the stylized output.

## Examples

### Example 1: Stylizing Artwork
- **Content Image**: `/content/drive/MyDrive/Ethics in AI/content/content10.jpg`
- **Style Image**: `/content/drive/MyDrive/Ethics in AI/style/69561.jpg`

### Example 2: Stylizing Landscape
- **Content Image**: `/content/drive/MyDrive/Ethics in AI/content/content10.jpg`
- **Style Image**: `/content/drive/MyDrive/Ethics in AI/style/style10.jpg`

### Example 3: Stylizing Characters
- **Content Image**: `/content/drive/MyDrive/Ethics in AI/content/spiderman.jpg`
- **Style Image**: `/content/drive/MyDrive/Ethics in AI/style/style13.jpg`

## Conclusion

This project showcases how Neural Style Transfer can be implemented using PyTorch, providing a creative tool to blend artistic styles with photographic content. Experiment with different images and parameters to explore diverse stylization effects.

---



