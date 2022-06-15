# brainMRI-ae

## Variational autoencoders for synthetic brain MRI images

This is a term paper for 3rd year of study at Faculty of Computer Science, Applied Mathematics and Information Science.

Prepared by Voronin Andrei Andreevich, supervised by Kondrateva Ekaterina Andreevna (4th year Ph.D. candidate in Skoltech)



### Abstract

Deep learning shows high potential for many medical image analysis tasks. Neural networks can work with full-size data without extensive preprocessing and feature generation and, thus, information loss. Recent work has shown that the morphological difference in specific brain regions can be found on MRI with the means of Convolutional Neural Networks (CNN). However, interpretation of the existing models is based on a region of interest and can not be extended to voxel-wise image interpretation on a whole image.
In the current work, we consider different methods of feature extraction and image compression applied to brain MRI images without any kind of preprocessed data. The main models that are studied in this work are convolutional autoencoders (AE) and variational convolutional autoencoders (VAE). These models are used to obtain low dimensional representations of original data (latent spaces) which are analyzed and used in problems of demographic signs of gender classification.

### Key words

Magnetic resonance imaging • Deep Learning • 3D CNN • Convolutional Autoencoders • Variational autoencoders • Demographic signs of gender classification


The current study aims to learn how to generate MRI data and study their low-dimensional representations in order to be able to bypass domain differences in prediction, or interpret pathologies using MRI. However, the global goal can be splitted into following subgoals:

- obtain low-dimensional representations of 3D medical images using autoencoder models
- study low-dimensional representations
- optimize the architecture and research

As an example of the practical use of autoencoders in this study, the
classification of demographic signs of gender is solved and the results are compared between different architectures.
