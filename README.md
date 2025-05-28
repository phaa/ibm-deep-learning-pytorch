# Advanced Deep Learning with PyTorch - IBM  

This repository contains code and notebooks developed during the [Advanced Deep Learning with PyTorch](https://www.coursera.org/learn/advanced-deep-learning-with-pytorch) course offered by IBM Skills Network through Coursera.  

<p align="center">
 <img src="https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/assets/logos/SN_web_lightmode.png" title="IBM Skills Network" width="400" />
</p>

## About the Course  
This course covers advanced Deep Learning concepts using PyTorch, focusing on modern architectures and essential techniques such as Convolutional Neural Networks (CNNs), Recurrent Neural Networks (RNNs), Long Short-Term Memory (LSTM) networks, Generative Adversarial Networks (GANs), and Transfer Learning.  
Since the course lectures and labs are in English, I chose to keep all code in the same language.

## Repository Structure  
The Jupyter notebook files are organized by modules, according to the course:
```
📁 Repository structure
├── 📁 1-cross-entropy
├── 📁 2-softmax
├── 📁 3-shallow-neural-networks
├── 📁 4-deep-neural-networks
├── 📁 5-convolutional-networks
├── 📁 6-projects
│ ├── 📝 Final Project - Image Classification with Transfer Learning
├── README.md
```

## Technologies Used  
- **Python**  
- **Jupyter Notebook**  
- **PyTorch**  
- **Torchvision**  
- **NumPy, Pandas**  
- **Matplotlib, Seaborn**  

## Final Project  
The final project is located in the **Module 5** folder and demonstrates the application of the main concepts learned throughout the course.

The project consists of building an image classifier using Transfer Learning, involving:

- **Data Exploration and Preparation:** Using a real-world image dataset, including preprocessing with `torchvision` transforms.
- **Transfer Learning:** Applying pre-trained models (such as ResNet or VGG) and adapting the final layers for a new classification task.
- **Training and Fine-Tuning:** Training the customized layers and fine-tuning convolutional layers to improve performance.
- **Model Evaluation:** Analyzing metrics such as accuracy, confusion matrix, and visualizing loss and accuracy curves during training.
- **GPU Utilization:** Implementing training with CUDA support for computational acceleration.

This project demonstrates practical skills in handling image datasets, building and fine-tuning deep learning models, as well as best practices when using PyTorch.

## How to Use  
1. Clone and access the repository:  
   ```bash
   git clone https://github.com/phaa/ibm-deep-learning-pytorch.git
   cd ibm-deep-learning-pytorch/
   ```
2. Activate the virtual environment (conda or venv):
   ```bash
   conda activate ibmenv
   ```
3. Run the notebooks in Jupyter lab:  
   ```bash
   jupyter lab
   ```
*Each notebook has a cell to install the necessary dependencies.* 

## Contributions  
This repository is a record of the course learning, but suggestions and improvements are always welcome!
