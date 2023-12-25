# Multimodal Emotion Recognition Using Deep Learning

## Project Overview
This repository hosts a machine learning project focused on emotion recognition through the processing of both visual and audio data. The project integrates advanced techniques in image and audio processing, and multimodal deep learning, using tools like OpenCV, ConvLSTM2D, Conv2D, and transfer learning models like VGG19 and YAMNet.

### Key Features
- **Visual Data Processing**: Transformation of emotional videos into images using temporal average frame rate sampling and facial recognition via OpenCV DNN ResNet.
- **Audio Data Processing**: Conversion of audio into spectrograms and extraction of over 40 audio features, including Mel-Frequency Cepstral Coefficients (MFCC).
- **Multimodal Model Construction**: Development of a model that processes audio and visual data, employing ConvLSTM2D and Conv2D for feature extraction, and fully connected layers for integration.

## Directory Structure
1. **data_augmentation**
   - Contains all processed and augmented images.
2. **modeling**
   - Includes Jupyter notebooks detailing the construction of the multimodal model.
3. **opencv_model**
   - Houses the OpenCV model used in the project.
4. **preprocessing**
   - Contains scripts and notebooks for image and audio data preprocessing.

## Implementation Details

### Visual Data Processing
- **Techniques**: Used OpenCV DNN ResNet for facial recognition and image cropping.
- **Goal**: Enhance feature quality for better model performance.

### Audio Data Processing
- **Approach**: Transformed audio data into spectrograms; computed features including MFCC.
- **Purpose**: Provide rich, detailed input data for convolutional neural networks.

### Multimodal Model Construction
- **Technologies**: Utilized ConvLSTM2D for video data and Conv2D for audio spectrogram feature extraction.
- **Transfer Learning**: Experimented with VGG19 and YAMNet for audio imagery.
- **Performance**: Achieved a 52% accuracy on the validation set.
