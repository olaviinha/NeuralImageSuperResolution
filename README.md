# Neural Image Super-Resolution (Colabs)

This is a collection of Colab Notebooks for various neural image enhancers in an attempt to enlarge low resolution images with restored details in high quality. All notebooks support batch processing of an entire directory. All notebooks were made to run in Google Colaboratory, using Google Drive as data source and storage.

## Latent Diffusion + FBCNN

**Colab for:** [Latent Diffusion](https://github.com/CompVis/latent-diffusion) + [FBCNN](https://github.com/jiaxi-jiang/FBCNN) <br>
**Papers:** High-Resolution Image Synthesis with Latent Diffusion Models https://arxiv.org/abs/2112.10752; Towards Flexible Blind JPEG Artifacts Removal https://arxiv.org/abs/2109.14573

Upscale by Latent Diffusion:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralImageSuperResolution/blob/master/Latent_Diffusion_Upscale.ipynb)

Sharpen by Latent Diffusion & remove JPEG artifacts by FBCNN (this notebook does not increase image resolution):

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralImageSuperResolution/blob/master/LatentDiffusionFBCNN.ipynb)

![image](https://user-images.githubusercontent.com/50331907/163679045-896ddcca-20aa-4392-a53d-637026b25cfd.png)

## ESRGAN

Works in Jun 2021.

**Colab for:** [JoeyBallentine's fork](https://github.com/JoeyBallentine/ESRGAN) of [BlueAmulet's fork](https://github.com/BlueAmulet/ESRGAN) of [ESRGAN by Xinntao](https://github.com/xinntao/ESRGAN). <br>
**Paper:** ESRGAN: Enhanced Super-Resolution Generative Adversarial Networks https://arxiv.org/abs/1809.00219

You can add more pretrained models from [upscale.wiki](https://upscale.wiki/wiki/Model_Database), probably.

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralImageSuperResolution/blob/master/SuperRes_ESRGAN.ipynb)

![image](https://user-images.githubusercontent.com/50331907/123541722-97416b80-d74e-11eb-9f50-8451100840d6.png)

## Older

Older notebooks are probably inferior and possibly outdated.

**Colab for:** [uperresolution_gan](https://github.com/fukumame/superresolution_gan). <br>
**Paper:** Photo-Realistic Single Image Super-Resolution Using a Generative Adversarial Network https://arxiv.org/abs/1609.04802

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralImageSuperResolution/blob/master/image_superres.ipynb) 

---

**Colab for:** [Neural Enhance](https://github.com/alexjc/neural-enhance) <br>
**Papers:** [See original repository](https://github.com/alexjc/neural-enhance#3-background--research)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/olaviinha/NeuralImageSuperResolution/blob/master/neural_enhance.ipynb) <br>





