# Internship Application - Jung Ji-ye's Portfolio

## Introduction
Welcome to my professional portfolio. This collection of work demonstrates my journey across system development and visual production, highlighting my technical competencies and creative endeavors.

## Table of Contents
- [Resume](#resume)
- [Project Overviews](#project-overviews)
- [Technological Contributions](#technological-contributions)
- [Visual Production Work](#visual-production-work)
- [Lectures and Collaborations](#lectures-and-collaborations)
- [Acknowledgements](#acknowledgements)
- [Contact Information](#contact-information)
- [Intellectual Property Declaration](#intellectual-property-declaration)

## Resume
Please find my resume attached which outlines my educational background, technical skills, and work history.
- [Jung_Jiye_Resume.pdf](#)

## Project Overviews

### 3D Reconstruction Project
**Description:** The project focused on 3D reconstruction from stereo data by estimating disparity maps from rectified images using the [2014 Stereo Datasets](https://vision.middlebury.edu/stereo/data/scenes2014/). The process included the computation of disparity using scanline approaches and similarity metrics, cross-checking, and ambiguity resolution. A significant aspect of the project was employing a Markov Random Field (MRF) via the [gco-wrapper](https://github.com/Borda/pyGCO) to refine the disparity maps, addressing inaccuracies and reconstructing depth maps under various conditions of lighting and exposure.

**Technologies Used:** Python, `Middlebury2014Stereo` from `torchvision.datasets`, `matplotlib`, `numpy`, `tqdm`, `gco`, `skimage.transform`

**Role:** Executed the end-to-end process from data acquisition and preprocessing to depth estimation and map refinement. Developed functions to automate the analysis for different image conditions, enhancing reproducibility and efficiency.

**Challenges and Solutions:** Encountered challenges in dealing with holes and noise in disparity maps. Overcame these by translating the disparity smoothing into an MRF problem and solving it with graph cuts, significantly improving the accuracy of the depth maps.

**Results and Impact:** Successfully generated and compared depth maps for selected image pairs, demonstrating the effectiveness of MRF in enhancing the quality of 3D reconstructions from stereo images.

### Variational Autoencoder (VAE) Project - VAE & Out-of-Distribution Detection
**Description:** This two-part project involved upgrading an autoencoder to a Variational Autoencoder (VAE) for the MNIST dataset and employing the VAE for out-of-distribution detection in histological brain data. The project aimed to improve upon the traditional autoencoder's performance and develop a method to identify data artifacts through anomaly detection. The implementation focused on spatial VAE architecture and iterative model refinement to accurately reconstruct high-resolution data and distinguish between corrupted and uncorrupted samples.

**Technologies Used:** Python, `numpy`, `matplotlib`, `torch`, `torchvision`, `torch.utils.data`, `cv2`, `os`, `torch.nn`, `torch.nn.functional`, `torch.optim`

**Role:** Led the development and evaluation of the VAE model, compared its performance to standard autoencoders, and applied the model to medical imaging data for artifact detection.

**Challenges and Solutions:** Addressed the challenge of modeling a VAE that can effectively reconstruct and differentiate data. Achieved by fine-tuning spatial VAE architecture and leveraging model optimization techniques.

**Results and Impact:** Established the efficacy of VAEs in high-quality image reconstructions and showcased their potential in medical imaging analysis, setting the stage for future integration with GANs for enhanced performance.

## Technological Contributions
Here, detail any contributions that showcase your programming and system design skills which may not involve graphics.

## Visual Production Work
Detail your work in visual production, such as video works, illustrations, and multimedia projects that demonstrate your artistic skills.

### TouchDesigner Visuals
**Fireball.toe**
**Description:** Created an interactive visual representation of a fiery sphere using TouchDesigner.
**Audioreactive.toe**
**Description:** Engineered an audio-reactive visual project to respond to sound dynamically.
**Role:** Complete conceptualization and execution.

### Video Projects
**Angel_project_Indiwamma.mp4**
**Description:** Contributed to the Bucheon Fantastic Film Festival through acting and directing in this video project.
**Music_Video_Ccumdori.mp4**
**Description:** Participated as an actor in a music video for a web drama, showcasing storytelling through performance.

## Lectures and Collaborations
Detail any lectures, educational contributions, or collaborative projects you have been involved with, specifying your role and contribution.

## Acknowledgements
My sincere appreciation goes out to all the individuals and teams who have provided guidance and collaboration throughout these
