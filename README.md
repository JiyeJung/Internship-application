# Contents Description

## Introduction
Welcome to my professional portfolio. This collection of work demonstrates my journey across system development and visual production, highlighting my technical competencies and creative endeavors.


## Table of Contents
- [3D Reconstruction Project](#3d-reconstruction-project)
- [Variational Autoencoder (VAE) Project](#variational-autoencoder-vae-project)
- [Brain Image Registration Project](#brain-image-registration-project)
- [Touchdesigner Work](#Touchdesigner-Work)
- [Angel Project Indie Wamma](#angel-project-indie-wamma)
- [Kkumdori Music Video](#kkumdori-music-video)
- [Artist Nest at the Art & Science Festival](#artist-nest-at-the-art--science-festival)


 - [Sub Folder](./Sub%20Folder) - Contains sample music and picturs for TouchDesigner projects and photos from the 'Artist Nest' exhibition.


## CV
- [CV_Jiye_Jung_2024.pdf](./CV_Jiye_Jung_2024.pdf)

## 3D Reconstruction Project
- [3D Reconstruction Project (Jupyter Notebook)](./3d_reconstruction_project.ipynb)

**Description:** The project focused on 3D reconstruction from stereo data by estimating disparity maps from rectified images using the [2014 Stereo Datasets](https://vision.middlebury.edu/stereo/data/scenes2014/). The process included the computation of disparity using scanline approaches and similarity metrics, cross-checking, and ambiguity resolution. A significant aspect of the project was employing a Markov Random Field (MRF) via the [gco-wrapper](https://github.com/Borda/pyGCO) to refine the disparity maps, addressing inaccuracies and reconstructing depth maps under various conditions of lighting and exposure.

**Technologies Used:** Python, `Middlebury2014Stereo` from `torchvision.datasets`, `matplotlib`, `numpy`, `tqdm`, `gco`, `skimage.transform`

**Role:** Executed the end-to-end process from data acquisition and preprocessing to depth estimation and map refinement. Developed functions to automate the analysis for different image conditions, enhancing reproducibility and efficiency.

**Challenges and Solutions:** Encountered challenges in dealing with holes and noise in disparity maps. Overcame these by translating the disparity smoothing into an MRF problem and solving it with graph cuts, significantly improving the accuracy of the depth maps.

**Results and Impact:** Successfully generated and compared depth maps for selected image pairs, demonstrating the effectiveness of MRF in enhancing the quality of 3D reconstructions from stereo images.

## Variational Autoencoder (VAE) Project
- [Variational Autoencoder (VAE) Project (Jupyter Notebook)](./VAE_project.ipynb)

**Description:** This two-part project involved upgrading an autoencoder to a Variational Autoencoder (VAE) for the MNIST dataset and employing the VAE for out-of-distribution detection in histological brain data. The project aimed to improve upon the traditional autoencoder's performance and develop a method to identify data artifacts through anomaly detection. The implementation focused on spatial VAE architecture and iterative model refinement to accurately reconstruct high-resolution data and distinguish between corrupted and uncorrupted samples.

**Technologies Used:** Python, `numpy`, `matplotlib`, `torch`, `torchvision`, `torch.utils.data`, `cv2`, `os`, `torch.nn`, `torch.nn.functional`, `torch.optim`

**Role:** Led the development and evaluation of the VAE model, compared its performance to standard autoencoders, and applied the model to medical imaging data for artifact detection.

**Challenges and Solutions:** Addressed the challenge of modeling a VAE that can effectively reconstruct and differentiate data. Achieved by fine-tuning spatial VAE architecture and leveraging model optimization techniques.

**Results and Impact:** Established the efficacy of VAEs in high-quality image reconstructions and showcased their potential in medical imaging analysis, setting the stage for future integration with GANs for enhanced performance.

## Brain Image Registration Project
- [Brain Image Registration Project (Jupyter Notebook)](./Brain_image_registration.ipynb)

**Description:** This project centered on enhancing the performance of the VoxelMorph network, a deep learning-based approach for medical image registration. Key improvements were achieved by exploring innovative loss functions designed to optimize the registration accuracy of brain tomography images. The project employed various loss functions, including the F-beta Loss, Log-cosh Dice Loss, and Structural Similarity Loss, each contributing uniquely to the alignment precision and robustness of the model.

**Technologies Used:** Python, Voxelmorph, TensorFlow, gco-wrapper, and various libraries for handling and processing medical images.

**Role:** Spearheaded the implementation and optimization of the VoxelMorph network. Responsible for testing and validating different loss functions to enhance model performance under varied imaging conditions.

**Challenges and Solutions:** The main challenge was addressing the non-convex nature of traditional loss functions, which can hinder the training of neural networks in image registration tasks. Solutions included the adaptation of the Log-cosh Dice Loss to mitigate this issue, providing a more robust and stable training process.

**Results and Impact:** The project demonstrated significant improvements in the accuracy and reliability of image registration. The exploration of different loss functions provided insights into their respective impacts on model performance, guiding future implementations and potential clinical applications. These advancements contribute to the broader field of computer vision and medical imaging by improving diagnostic capabilities and treatment planning.


## Touchdesigner Work



### Fireball.toe
- [ Fireball Project (TouchDesigner)](./Fireball.toe)

**Description:** Developed a visually engaging representation of a sphere surrounded by dynamic flames, which simulates the effects of a magnetic field or gravity. This piece features the sphere in constant rotation with changing colors, created using Feedback and Edge in TouchDesigner. While not interactive, this project focuses on visual aesthetics and dynamic behaviors in a simulated environment.

**Role:** Responsible for the complete design and development of the visual effects, ensuring seamless transitions and vibrant color changes to enhance the visual appeal.

**Challenges:** The main challenge was determining the optimal combination of parameters within TouchDesigner's operators to produce meaningful and visually appealing changes.

**Results and Impact:** This project served as a valuable exploration into the capabilities of TouchDesigner, enhancing my skills in visual programming and digital art creation.

### Parrot.toe
- [ Parrot Project (TouchDesigner)](./Parrot_splash.toe)

### Description
This project creatively leverages TouchDesigner to animate a parrot image with sophisticated particle effects and semi-transparent overlays. Using the Particle GPU and Matte operators, it emphasizes the intricate balance of transparency and image depth, enhancing the visual appeal through the layering of these elements.

### Role
I was responsible for the entire project, from conceptual design to implementation. My focus was on using the Matte operator to achieve seamless integration of particle effects with the static image, ensuring that each element complemented the other without dominating the visual space.

### Challenges
Mastering the Matte operator to finely control the transparency and interaction between the particle layers and the parrot image was a significant challenge. This required careful adjustment of parameters to maintain visual harmony throughout the animation.

### Results and Impact
This project enhanced my proficiency in TouchDesigner, especially in manipulating visual elements like particle systems and transparency. It showcased the practical application of complex visual programming in creating aesthetically compelling digital artworks.


### audio_spectrum.toe 
- [ Audio Reactive Project (TouchDesigner)](./AudioSpectrum.toe)

**Description:** This project showcases an immersive, interactive color spectrum flowing dynamically with the beats of music, brought to life using TouchDesigner's feedback operation. It presents a visual symphony, orchestrated through the modulation of colors and movement in harmony with the audio input, reflecting the essence of the sound in a vivid visual language.


**Role:** Led the implementation of the interactive elements using Feedback and PBR in TouchDesigner, focusing on real-time audio responsiveness.

**Challenges:** The challenge was fine-tuning the responsiveness of the visuals to various audio inputs, requiring meticulous adjustments to ensure synchronization and visual impact.

**Results and Impact:** This piece not only showcases the potential of interactive visual art but also significantly contributed to my understanding and proficiency with TouchDesigner, particularly in creating audio-responsive environments.



**Technologies Used(Fireball,Audio_spectrum,Parrot):** 
TouchDesigner
Referencing tutorials by Noto and Pao Olea


## Angel Project Indie Wamma
- [ Angel Project Indie Wamma](./Angel_project_Indiwamma_480.mov)
**Description:** Directed by Lim Ho-kyung, this series of video pieces was a collaborative fusion of performance and poetry funded by a public contest by the Korea Foundation for the Arts in 2021. My role encompassed production, direction, editing, acting, and narration across all five pieces. These works were a submission to the Bucheon International Fantastic Film Festival, showcasing the interplay of video, music, and narrative.

**Technologies Used:** Final Cut Pro

**Challenges:** The intricate task of blending video, music, and narration into a cohesive experience was a creative hurdle that I thoroughly enjoyed overcoming.

**Results and Impact:** The final production was a testament to the power of interdisciplinary collaboration and received notable attention at the film festival.

## Artist Nest at the Art & Science Festival
- [ Artist Nest at the Art & Science Festival (Image)](./Artist_Nest.jpeg)


**Description:** As a significant part of the 2019 Art & Science Festival in Daejeon, Korea, Artist Nest was a convergence of dance, visual art, and science. My role was coordinating the event's planning and program, overseeing the installation and maintenance of media art works, including projection mapping using high-ANSI projectors.

**Technologies Used:** Projection Mapping Techniques, Media Art Installations

**Challenges:** Precise adjustments of projection mappings on a vast stage backdrop and unforeseen operational mishaps required quick problem-solving and meticulous attention to detail.

**Results and Impact:** The festival attracted nationwide attention and bolstered Daejeon City's commitment to fostering the intersection of art and science. My management of notable exhibitions like 'City of Sound' and 'Formation of the City' contributed to the festival's interactive and immersive experience.

<img src="Sub%20Folder/Artist_Nest_formation_of_the_city_1.jpeg" width="400" alt="Formation of the City 1"/>
<img src="Sub%20Folder/Artist_Nest_formation_of_the_city_2.jpeg" width="400" alt="Formation of the City 2"/>
<img src="Sub%20Folder/Artist_Nest_city_of_sound.jpeg" width="400" alt="City of Sound "/>
<img src="Sub%20Folder/Artist_Nest_performance_Alice.jpg" width="400" alt="Performance Alice"/>




### Kkumdori Music Video
- [ Kkumdori Music Video](./MusicVideo_Kkumdori.mp4)

**Description:** This music video was a compilation of scenes from a web drama I acted in during 2021. My contributions to the production included both acting and assistance in editing, working to ensure thematic consistency across various scenes.

**Technologies Used:** Final Cut Pro

**Challenges:** Creating a unified narrative from disparate scenes and applying visual effects that accurately conveyed the intended emotions proved to be challenging yet fulfilling.

**Results and Impact:** The music video served as an amalgamation of storytelling and acting, providing a visual complement to the web drama's narrative.


