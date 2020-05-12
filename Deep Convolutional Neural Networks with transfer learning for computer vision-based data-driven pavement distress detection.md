# Deep Convolutional Neural Networks with transfer learning for computer vision-based data-driven pavement distress detection
Kasthurirangan Gopalakrishnan , Siddhartha K. Khaitan, Alok Choudhary, Ankit Agrawal    
**Status**: Skimmed

**Reading Status:** Skimmed

## Highlights
- Pre-trained deep Convolutional Neural Networks (DCNN) were used for crack detection.
- Pavement images sampled from the FHWA/LTPP database were used as datasets [**where could I get this??**]
- The truncated **VGG-16 DCNN** was used as a deep feature generator for road images.
- Various machine learning classifiers were trained using the semantic image vectors. [**comparison for benchmarking?**]
- A neural network classifier trained on deep transfer learning vectors gave the best results 
- Employs traditional ML techniques on the Semantic Image Vectors for Crack or No Crack Detection

## Quick CopyPasta Info Dump
- Two software-based approaches to pavement crack detection workflow are common: manual typically developed in-house and used by public agencies at the project
level) and semi-automatic typically developed and provided by private vendors at the network level)
- Current limitations to the existing crack detection methods is the inability to overcome inherent challenges associated
with these pavement images, such as inhomogeneity of cracks, diversity of surface texture (eg., tining), background complexity,
presence of non-crack features such as joints, etc.
- The **goal of this research study** is to develop a simplified visionbased pavement crack detection system by using a pre-trained
deep learning model to detect cracks from pavement images through transfer learning and domain adaptation approach
- 2048 x 3072 digital image from FWHA, 1056 pavement images
- VGG16 Image Input Size si 224x224. Dataset is transformed into 1000 x 500

## NSDB
### Need
-  

### Solution

### Differentiation

### Benefit

### Comments
- Good RRL outline: intensity-thresholding, edge detection, wavelet transforms, texture-analysis, and machine learning techniques
- RRL includes traditional ML such as clustering in CrackIt (can be used for RRL)
- Very unclear, looks like they are training a classifier than a detector?
