# AutoShield


# Safeguarding Neural Networks: Autoencoders as Defense

![Project Image](insert_image_url_here)

## Overview

This project, titled "Safeguarding Neural Networks: The Power of Autoencoders as Defense," addresses the growing concern of adversarial attacks on machine learning models. With the increasing use of state-of-the-art machine learning and deep learning models in various applications, it has become crucial to protect these models from adversarial attacks that can compromise their performance.

## Abstract

In recent years, machine learning models have become integral in our daily lives, from recommendation systems to complex applications like understanding the protein structure of the COVID virus and self-driving cars. However, these models are vulnerable to adversarial attacks, where subtle changes to input data can lead to incorrect predictions. This project explores the effectiveness of using autoencoders to detect anomalies and adversarial examples in machine learning models. By employing two autoencoders sequentially, we aim to eliminate perturbations in input data and enhance model resilience.

## Key Objectives

- Investigate the vulnerability of machine learning models to adversarial attacks.
- Evaluate the robustness of autoencoders in detecting and mitigating adversarial examples.
- Assess the performance of two autoencoders working in tandem to remove perturbations.
- Improve the accuracy and reliability of machine learning models in the presence of adversarial attacks.

## Experimental Setup

### Dataset

The project utilizes the MNIST dataset, containing handwritten digits from 0 to 9 as grayscale images. It consists of a training set of 60,000 images and a test set of 10,000 images.

### Methodology

- A classifier model is employed to assess model accuracy in the presence of adversarial attacks.
- Two autoencoders are used in sequence to denoise adversarial images.
- Fast Gradient Sign Method (FGSM) and Projected Gradient Descent (PGD) attacks are applied to generate adversarial images.
- The performance of the autoencoders is evaluated using various metrics, including image quality measures, classification accuracy, and perceptual similarity.

## Results

The project found that the classifier's accuracy on adversarial images was significantly improved after denoising with two stacked autoencoders. The accuracy for FGSM increased to 0.8532, and for PGD, it increased to 0.8688. A single autoencoder also showed substantial improvements with an accuracy of 0.8314 for FGSM and 0.8572 for PGD.

## Conclusion

This project demonstrates the effectiveness of using autoencoders as a defense mechanism against adversarial attacks on machine learning models. By denoising adversarial images, autoencoders significantly enhance the accuracy and robustness of the model. Using two autoencoders in sequence yields the best results, highlighting the potential of this approach to bolster model resilience.



## Future Work

The project suggests further research avenues, including exploring different architectures for the second autoencoder and using a more complex classifier to understand the effects of adversarial attacks on neural networks with deeper layers and neurons.

---

This README provides an overview of the project "Safeguarding Neural Networks: Autoencoders as Defense." For more detailed information and references, please refer to the project documentation.
