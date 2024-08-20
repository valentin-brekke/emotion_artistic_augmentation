# Emotion-Driven Artistic Augmentation of Human Faces

This project integrates computer vision and artistic expression to augment images by reflecting human emotions through art. It creates a pipeline that detects a face, classifies the individual’s emotion, and applies a corresponding artistic style using neural style transfer. The goal is to develop personalized artworks that visually represent the subject’s emotional state, enhancing both affective computing and digital art interaction.

## Project Inspiration

Inspired by Zach Lieberman’s work on “Más Que La Cara,” this project explores using art as a medium for emotional expression and personal interaction with the styles of world-renowned artists. It aims to personalize the artistic augmentation of images, focusing on the emotional state of individuals, which is often overlooked in traditional style transfer applications.

## Methodology

- **Face Detection:** Utilizes MediaPipe for efficient face detection within images, ensuring the subject is ready for emotion classification.
- **Emotion Classification:** Employs Convolutional Neural Networks (CNNs) and Vision Transformers (ViTs) to identify emotions from facial expressions.
- **Style Transfer:** Applies artistic styles corresponding to detected emotions using the method developed by Gatys et al. This involves extracting and combining content and style features from images.

![Pipeline Overview](images/pipeline_overview.png)
