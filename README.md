# Signature-Generation-Using-Variational-Autoencoder-VAE-and-GAN

# RESEARCH PAPER
[Tayyab_question_1_report.pdf](https://github.com/user-attachments/files/17556778/Tayyab_question_1_report.pdf)


# Project Overview
This project aimed to develop and train two deep learning models—a Variational Autoencoder (VAE) and a Generative Adversarial Network (GAN)—to generate synthetic signatures. Both models were trained separately to produce fake signatures by sampling from the latent space. To improve dataset variety, signature augmentation techniques like scaling, rotation, and noise addition were employed. The performance of the generated signatures was assessed using metrics such as reconstruction loss, helping determine the similarity between the generated and original signatures.

#Tools and Technologies Used

Programming Language: Python


# Libraries:

TensorFlow/Keras: For constructing and training the VAE and GAN models.

NumPy: For data manipulation and matrix operations.

OpenCV/PIL: For image processing and augmentation tasks.


# Techniques:

### Variational Autoencoder: For learning latent representations and generating signatures.

### Generative Adversarial Network: For generating realistic-looking signatures through adversarial training.

### Image Augmentation: Including scaling, rotation, and noise addition to enhance the diversity of the training dataset.

### Latent Space Sampling: Sampling points from the latent space to generate new signatures.

### Reconstruction Loss Evaluation: To quantify how closely the generated signatures resemble the original samples.

This project successfully showcases how VAE and GAN can be applied in tandem with image augmentation to create realistic synthetic data for signature verification and related applications.
