# Image Denoising Autoencoder

## Description

The **Image Denoising Autoencoder** project leverages deep learning techniques to enhance image quality by removing noise from images. The core of the project is an autoencoder model built using TensorFlow and Keras, designed to clean noisy images by learning from a dataset of paired noisy and clean images. 

### Key Features:
- **Image Denoising**: Uses a convolutional autoencoder to transform noisy images into cleaner versions.
- **Model Training**: Trained using a dataset of noisy and clean image pairs with early stopping and model checkpointing to ensure optimal performance.
- **Performance Evaluation**: Assesses model performance through PSNR (Peak Signal-to-Noise Ratio) metrics and visual comparison of denoised images.
- **Text Extraction**: Applies Tesseract OCR to extracted images to demonstrate the practical use of denoised images in text recognition tasks.

### How It Works:
1. **Data Loading and Preprocessing**: Images are loaded, resized, and normalized from specified directories.
2. **Autoencoder Architecture**: Consists of an encoder that compresses images into a lower-dimensional representation and a decoder that reconstructs the image from this representation.
3. **Model Training**: The autoencoder is trained to minimize reconstruction error between noisy input images and their clean counterparts.
4. **Evaluation and Visualization**: The model's performance is evaluated by comparing PSNR values of original, cleaned, and predicted images, and the results are visualized.
5. **Text Recognition**: Denoised images are processed using Tesseract OCR to extract and display text, showcasing the practical applications of the cleaned images.

"# Image-Denoising-Autoencoder" 
