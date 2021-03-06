# **Polytechnique Montréal - INF8225 - I.A. : tech. probabilistes et d’apprentissage**

![Polytechnique Montréal Logo](https://upload.wikimedia.org/wikipedia/commons/c/cf/Polytechnique_Montreal_Logo.jpg)

## **Final Project : ResNet meets Split-Attention: replication, ablation and analysis of ResNeSt**

### **Students involved:**

| Name     | Email          |
| -------- | -------------- |
| Emilie Ouraou     | emilie.ouraou@polymtl.ca |
| Cyprien Quéméneur | cyprien.quemeneur@polymtl.ca |
| Hugo Rodet        | hugo.rodet@polymtl.ca |

### **Abstract**

In this work, we present a reproducibility study of the paper _ResNeSt: Split-Attention Networks_. We have successfully replicated the results presented in the article on the tasks of image classification, segmentation and object detection. The ablation study and transfer learning experiments were also reproduced and the author's claims have been verified. We draw the conclusion that ResNeSts are indeed a substantial improvement over ResNets and could replace them in most cases.

### **Overview**

ResNeSt is an architecture of neural networks, applied to computer vision, proposing a mix between a modern convolutive neural network (CNN), the ResNest, as well as the attention mechanism. For our final project we propose a study of the article which introduced the ResNeSts. This work indirectly follows our article presentation which focused on vision transformers (ViTs).

### **Image classification**

As a baseline model, a ResNeSt is trained for image classification. The notebook _ResNeSt_classification.ipynb_  reproduces the experiments on the ImageNet dataset, using the pretrained models made available by the authors of the original article (all rights reserved). Furthermore, we additionally examine the influence of the batch size on the final results and reproduce the ablation study conducted in the original article.

A complete guideline is found in the notebook, however **the results and conclusions are found in the final report, which is written under an article format**.

### **Transfer learning**

ResNeSts can be trained as a general model on image classification then fine-tuned on more downstream tasks (aka transfer learning). The notebook _ResNeSt_TransferLearning.ipynb_  reproduces the experiments on semantic segmentation, instance segmentation and object detection, using the pretrained models made available by the authors of the original article (all rights reserved).

A complete guideline and some analyses are found in the notebook. **However it is not a substitute to the final report, which is written under an article format.**

**Disclaimer:** opening this notebook directly into GitHub will display the entire content of the cells, as it is extremely lengthy this will severely complexify the reading of the notebook. We strongly encourage you to download this notebook locally and open it with jupyter before attempting to examine it.

### **Discussion**

This project is not akin to the projects we have conducted to this day. We tried to be original and didn't develop a model ourselves per se. Ultimately, this project was less about coding, as done in practical works, and more about navigating the complex documentation, divided amongst many repositories and websites, of a state-of-the-art deep learning model and exploring real-world datasets and frameworks. Consequently, the experiments were also more computationally intensive when compared to what we are used to, and we had to remain modest in our protocol. Moreover, this was also an opportunity for us to get more accustomed to more downstream computer vision tasks, with whom we were not necessarily familiar. All in all this project taught us a lot and we hope it will be to your liking.


### **References**
Reference to the main article:
* [ResNeSt: Split-Attention Networks](https://arxiv.org/abs/2004.08955)

References to the repositories:
* [ResNeSt main repository](https://github.com/zhanghang1989/ResNeSt)
* [Detectron2](https://github.com/facebookresearch/detectron2)
* [PyTorch-Encoding](https://github.com/zhanghang1989/PyTorch-Encoding)

References to the datasets:
* [ImageNet](https://www.image-net.org/)
* [ADE20k](https://groups.csail.mit.edu/vision/datasets/ADE20K/)
* [COCO](https://cocodataset.org/#home)
* [CityScapes](https://www.cityscapes-dataset.com/)

Other relevant references:
* [PyTorch-Encoding for semantic segmentation](https://hangzhang.org/PyTorch-Encoding/model_zoo/segmentation.html)
* [GluonCV toolkit for segmentation](https://cv.gluon.ai/model_zoo/segmentation.html)

### **Additional links**
* [Original project proposal](https://drive.google.com/file/d/1bUFPHQVaruLdaGRoMs8sUy3j7MxUNEFn/view?usp=sharing)
* [Mid-project video presentation](https://drive.google.com/file/d/1b_tTK4U43sqDPoSfZIHlQlq5FmQVfShV/view)
* [Mid-project slides](https://docs.google.com/presentation/d/1OOntCfKOc4PJQYAgF1DrbPcqWN2mSw5j/edit?rtpof=true&sd=true)
* [Final report and slides](https://drive.google.com/drive/folders/1Drc5JKEhdDWyBesZNelBS8XefGZENRBL?usp=sharing)
