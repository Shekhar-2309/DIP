# SteganoGraphy using Deep Learning 
This repository contains the literature review for our project.

This repo contains:

Steganography Using Deep Learning document.

Research papers

The existing traditional image steganography methods often adopt the selection and mapping approaches. Among all the pixels of the cover image, only those which have the portability of incorporating the secret bits without noticeable distortion are chosen. This results to small integration capacity. In this paper, we propose a generic system of image steganography that uses the architecture of auto-encoding networks based on end to end trained deep Convolutional Neural Networks to ensure the process of concealment and extraction. The trained network includes two sub-networks, one for hiding used by the sender to encode a color image in another of the same size. The other for extraction, used by the recipient to retrieve the secret image from the received stego image.

futureinternet-10-00054-v2: This paper combines recent deep convolutional neural network methods with image-into-image steganography. It successfully hides the same size images with a decoding rate of 98.2% or bpp (bits per pixel) of 23.57 by changing only 0.76% of the cover image on average

IMAGE STEGANOGRAPHY USING CNN: The main goal of this paper is to explore and discuss various deep learning methods available in image steganography field. Deep learning techniques used for image steganography can be broadly divided into three categories - traditional methods, Convolutional Neural Network-based and General Adversarial Network-based methods.

Image Steganography Analysis Based on Deep Learning: Unlike many popular steganographic methods that encode the secret message within the least significant bits of the carrier image, our approach compresses and distributes the secret image’s representation across all of the available bits.

Datasets

Linaeus 5 Image 
 Dataset:https://chaladze.com/l5/#:~:text=Overview&text=Images%20are%20256x256%20pixels%2C%20color,400%20test%20images%20per%20class
5 classes: berry, bird, dog, flower, other (negative set)
Images are 256x256 pixels, color (downsampled versions: 128X128, 64X64 and 32X32 pixels).
1200 training images, and 400 test images per class.
Images were downloaded from pixabay.com.
