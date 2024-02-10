# Deep-Classical-Music

# Overview 
This project focuses on exploring methods to generate Indian Classical music without lossing its original attributes. Currently we have explored unconditional and conditional generation using Jukebox methodoloy. This repo contains the training code for the same. In future, we will add more methods because with the dawn of Generative AI, new methods for audio generation are researched and implemented day by day.  

## TODO 
- [x] Upload the colab notebook for inference of Jukebox model 
- [x] Upload relevant links to dataset and checkpoints
- [ ] Upload the colab notebook for training of VQ-VAE and Upsamplers which make up the Jukebox model
- [ ] Make the code modular and train on more hardware
- [ ] Explore other methods for audio generation

# Setup

## Dataset

### **Flute Dataset**

This is the unlabelled flute and tabla dataset collected from youtube majorly from the artist Hariprasad Chaurasia.  
Run the following command to download the dataset:
```
!gdown --id 1qWBDK_SoMo471OycIwntjg1Qxx0fbgsu
!unzip flute_dataset.zip
!rm flute_dataset.zip
```

## Pretrained Checkpoints 

It is advised to store checkpoints in the following structure for easier access and readability. 
```
content 
| - checkpoints 
  | - vqvae
  | - prior
```

### **VQ-VAE**

Run the following command:
```
!gdown --id 1WQc4vOJXilI7gnn0iyKREe7AVcSKKpP1
```

### **Prior**

Run the following command:
```
!gdown --id 1NahRriZJIPtZsFtFN9vOakVzgX5_mbzu
```

# Inference

Uploaded inference.ipynb for generating samples in two ways : 
- Ancestral Sampling 
- Primed Sampling

Here is the live version of the notebook : <a href="https://colab.research.google.com/drive/1CcBV_h8J9KK1kCztlIi_p6nTvYCWplvM?usp=sharing">
<img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Image" style="display: block; margin: 0 auto" />
</a>

# Credits  
[Jukebox](https://github.com/openai/jukebox) - A Generative Model for Music

# Support 
There are many ways to support a project - starring⭐️ the GitHub repo is just one.
