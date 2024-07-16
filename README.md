# Objectives of the project:
The main objective of this work is to propose deep learning-based methods for binary image classification (True/Fake) and then to evaluate the performance of these implemented approaches.

# The implemented approaches
In this project we have implemented 3 distinct approaches, each based on a very specific technique:

- Direct approach (CNN)
- Frequency approach (Fourier spectrum)
- Dimensionality reduction approach (Auto-encoder)

# Datasets
We used 5 main datasets to perform this work:

- **For the real images**
  -  The IMDB-WIKI dataset. [Dataset link](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/static/wiki_crop.tar), [Scientific Paper](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/)


- **For the fake datasets**
  - Deep Fake Face (DFF) [Hugging Face](https://huggingface.co/datasets/OpenRL/DeepFakeFace):
    - Inpainting: Inpainting stable diffusion 
    - Text2image: Stable diffusion v1.5
    - Insight: Toolbox InsightFace

  - 140k Real and Fake faces (Available on [Kaggle](https://www.kaggle.com/datasets/xhlulu/140k-real-and-fake-faces))
 
  # Datasets distribution with PCA

  ![PCA data distribution](https://github.com/Malekbennabi3/TER_Notebooks/blob/main/img/Acp.png)
  
  The data were displayed to make sure that the different datasets are interlaced and not linearly separable, in such a way that the model differentiates them by characteristics.

  # Approaches

  -  ![Direct approach](https://github.com/Malekbennabi3/TER_Notebooks/blob/main/img/direct.png)
  -  ![Fourier approach](https://github.com/Malekbennabi3/TER_Notebooks/blob/main/img/fourier.png)  

