# [ SRGAN for chestXray](https://github.com/amousavi9/SRGAN-For-chestXray)
Chest X-ray (CXR) imaging is one of the most widely-used and cost-effective technology for chest screening and diagnosis of Pulmonary diseases. An always concerned improvement about CXR is to reduce X-ray radiation while achieving ultra-high quality imaging with fine structural details since CXR involves ionizing radiation and tolerance of different populations. This work applies SRGAN to accurately recover high-resolution (HR) CXR images from low-resolution (LR) counterparts. We train the Model on the COVID-19 radiography database dataset from [Kaggle](https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia).

# Architecture
The generator creates a high-resolution (HR) image (4x upscaled) from a corresponding low-resolution (LR) image. The discriminator distinguishes the generated (fake) HR images from the original HR images.
<p align="center">
  <img src="https://github.com/amousavi9/SRGAN-For-chestXray/blob/main/results/srgan-architecture.png" width="860" height="430" />
</p>

# Results
<p align="center">
  <img src="https://github.com/amousavi9/SRGAN-For-chestXray/blob/main/results/4800.png" width="810" height="300" />
</p>

<p align="center">
  <img src="https://github.com/amousavi9/SRGAN-For-chestXray/blob/main/results/4950.png" width="810" height="300" />
</p>

<p align="center">
  <img src="https://github.com/amousavi9/SRGAN-For-chestXray/blob/main/results/4900.png" width="810" height="300" />
</p>

<p align="center">
  <img src="https://github.com/amousavi9/SRGAN-For-chestXray/blob/main/results/4850.png" width="810" height="300" />
</p>

<p align="center">
  <img src="https://github.com/amousavi9/SRGAN-For-chestXray/blob/main/results/4300.png" width="810" height="300" />
</p>
