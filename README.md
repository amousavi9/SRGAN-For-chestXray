# [ SRGAN for chestXray](https://github.com/amousavi9/SRGAN-For-chestXray)
Chest X-ray (CXR) imaging is one of the most widely-used and cost-effective technology for chest screening and diagnosis of Pulmonary diseases. An always concerned improvement about CXR is to reduce X-ray radiation while achieving ultra-high quality imaging with fine structural details since CXR involves ionizing radiation and tolerance of different populations. This work applies SRGAN to accurately recover high-resolution (HR) CXR images from low-resolution (LR) counterparts. We train the Model on the COVID-19 radiography database dataset from [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).

# Architecture
The generator creates a high-resolution (HR) image (4x upscaled) from a corresponding low-resolution (LR) image. The discriminator distinguishes the generated (fake) HR images from the original HR images.
<p align="center">
  <img src="https://github.com/amousavi9/SRGAN-For-chestXray/blob/main/results/srgan-architecture.png"/>
</p>

# Loss function
SRGAN uses a perceptual loss function which consists of an adversarial loss and a content loss. The adversarial loss pushes the solution to the natural image manifold using a discriminator network that is trained to differentiate between the super-resolved images and original photo-realistic images. The content loss is a L2 distance between the features of the base image (extracted by a VGG-19 network) and the features of the combination image, keeping the generated image close enough to the original one.
<p align="left">
  <img src="https://github.com/amousavi9/SRGAN-For-chestXray/blob/main/results/loss-func.PNG" width="745" height="275" />
</p>

# Results
### After 4000 Epochs (with batch size 1)
<p align="center">
  <img src="https://github.com/amousavi9/SRGAN-For-chestXray/blob/main/results/4800.png" />
</p>
<p align="center">
  <img src="https://github.com/amousavi9/SRGAN-For-chestXray/blob/main/results/4950.png" />
</p>
<p align="center">
  <img src="https://github.com/amousavi9/SRGAN-For-chestXray/blob/main/results/4900.png" />
</p>
<p align="center">
  <img src="https://github.com/amousavi9/SRGAN-For-chestXray/blob/main/results/4850.png" />
</p>
<p align="center">
  <img src="https://github.com/amousavi9/SRGAN-For-chestXray/blob/main/results/4300.png" />
</p>
