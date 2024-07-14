**Notice (07/12/2024)**: This repository is currently under maintenance. You can download the dataset using the links provided below. Additional code for data visualization and analysis will be updated soon. All materials are licensed under the MIT License.

# RefCOCO-Gaze Dataset

![refcocogaze-teaser](https://drive.google.com/uc?export=view&id=1U67rmU4MLBOCc9ASAnIttwlZhXdwPoUN)

We introduce a large-scale dataset of speech-driven human eye movements, where they see an image and hear a referring expression defining the object in the scene (e.g., guy in back left wearing black). 

RefCOCO-Gaze is a laboratory-quality dataset large enough to train deep-network models, including 19,738 human gaze scanpaths, corresponding to 2,094 unique image-expression pairs, from 220 participants performing object referral task.

RefCOCO-Gaze aims to advance research in human gaze prediction by moving beyond simple visual tasks (such as free-viewing or search) to more naturalistic and ecologically valid contexts that use language. We hope this dataset facilitates the development of a computational model that predicts and explains how spoken language guides moment-by-moment human attention control. This understanding will benefit various HCI systems that must effectively interact with humans by predicting their gaze in natural multimodal setups.

We hope you enjoy using RefCOCO-Gaze! 🎉

---
# Download:

RefCOCO-Gaze consists of 19,738 scanpaths that were recorded while 220 participants with normal or corrected-to-normal vision viewed 2,094 COCO images and listened to the associated referring expressions from the RefCOCO dataset. 

The gaze data, recorded by an EyeLink 1000 eyetracker, includes information about the location and duration of each fixation, the bounding box of the search target, audio recordings of the referring expressions, the timing of the target word, and the synchronization between the spoken words and the sequence of fixations (tells us which word triggered which fixations). RefCOCO-Gaze covers a diverse range of linguistic and visual complexity, making it an ideal dataset for researchers studying human integration of vision and language, and HCI researchers alike. 

- Image Stimuli (.zip; Size: 1680x1050) [Download](https://drive.google.com/uc?id=1gOC2XMH8IIwwev0L0SmoyQRr7fYP_e60&export=download)
- Sound Files (.zip) [Download](https://drive.google.com/uc?id=1gRwUc1LVkP-pSpH0LnXYVpWii6PLPk9u&export=download)
- Word Onset Timing (.json) [Download](https://drive.google.com/uc?id=1PR1zvXA4NHijTOzmWSYgFyDNBIFFz8aJ&export=download)
- Training Gaze dataset (.json) [Download](https://drive.google.com/uc?id=1TYEe174rUCfPrdw6ZZcmfbpn692kC_U1&export=download)
- Validation Gaze dataset (.json) [Download](https://drive.google.com/uc?id=1TYi9qrGAn2jqPfAPn5LlBFxRNJ828chg&export=download)
- ~~Testing Gaze dataset [Download]~~ --> 🔊We are taking down the testing data in order to set up an online benchmark, stay tuned!

If you use RefCOCO-Gaze, please cite:

```
@InProceedings{Mondal_2024_ECCV,
author = {Mondal, Sounak and Ahn, Seoyoung and Yang, Zhibo and Balasubramanian, Niranjan and Samaras, Dimitris and Zelinsky, Gregory and Hoai, Minh},
title = {Look Hear: Gaze Prediction for Speech-directed Human Attention},
booktitle = {European Conference on Computer Vision (ECCV)},
year = {2024}
}
```
