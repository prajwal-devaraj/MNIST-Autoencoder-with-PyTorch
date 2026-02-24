# VISUAL AUTOREGRESSIVE MODELING SCALABLE IMAGE GENERATION VIA NEXT-SCALE PREDICTION

MNIST Autoencoder with PyTorch
This project demonstrates how to build and train a simple convolutional autoencoder using PyTorch on the MNIST dataset. The autoencoder learns to compress and reconstruct handwritten digit images, providing a foundation for tasks like dimensionality reduction, denoising, or generative modeling.

What This Code Does

- Loads and preprocesses the MNIST dataset, resizing images from 28×28 to 16×16.

- Defines a lightweight convolutional autoencoder with encoder and decoder blocks:

- Encoder compresses the input from 16×16 to 4×4 using Conv2d layers.

- Decoder reconstructs the original size using ConvTranspose2d layers.

- Trains the model using Mean Squared Error (MSE) loss and the Adam optimizer.

- Visualizes results by comparing original and reconstructed images side-by-side.

- Saves the result as a PNG image (reconstruction_result.png).

Technologies Used

- Python 

- PyTorch 

- torchvision

- Matplotlib 

How to Run

Install required packages:

pip install torch torchvision matplotlib

Run the script:

python autoencoder_mnist.py

View the reconstruction output in the saved image:

Output Sample

The script saves a comparison image showing original vs. reconstructed MNIST digits:
```
| Original Digits | → | Reconstructed Digits |

```

pdevaraj001@gmail.com
