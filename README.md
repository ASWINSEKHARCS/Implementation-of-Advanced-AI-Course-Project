ULTRASOUND IMAGE RECONSTRUCTION: U-NET VS. VISION TRANSFORMER

OVERVIEW
This project explores the use of deep learning models, specifically U-Net and Vision Transformer, for reconstructing ultrasound images. The implementation compares the effectiveness of these architectures in medical imaging applications, focusing on enhancing image quality and reconstruction accuracy.
FEATURES
•	Data Preparation: Includes normalization, resizing, and augmentation techniques tailored for ultrasound images.
•	Model Architectures: 
o	U-Net: A convolutional neural network optimized for image segmentation and reconstruction tasks.
![image](https://github.com/user-attachments/assets/b375891b-9c24-4c11-887b-4393e802843b)
o	Vision Transformer (ViT): A cutting-edge model leveraging self-attention mechanisms for image-based tasks.
![image](https://github.com/user-attachments/assets/2fbcae0c-e3f4-4dc3-b4e6-6dd729180877)
•	Training Pipeline: 
o	Custom loss functions for medical image reconstruction
o	Performance metrics to evaluate model outputs
•	Comparison & Visualization: 
o	Side-by-side analysis of reconstructed images
o	Quantitative metrics for evaluating reconstruction quality
REQUIREMENTS
To run this project, you need the following dependencies:
•	Python 3.8 or later
•	Jupyter Notebook
•	TensorFlow or PyTorch (version compatible with Vision Transformers)
•	Additional libraries: numpy, matplotlib, opencv-python, scikit-learn
FILE STRUCTURE
•	Ultrasound_Image_Reconstruction_UNet_Vs_VisionTransformer.ipynb: Main notebook containing all code for data processing, model implementation, training, and evaluation.
•	models: Saved weights for the trained best U-Net and Vision Transformer models.
•	results: Folder containing reconstructed images and performance metrics 

How to Run
1.	Clone this repository: 
2.	git clone https://github.com/ASWINSEKHARCS/Implementation-of-Advanced-AI-Course-Projectcd ultrasound-reconstruction
3.	Open the Jupyter notebook: 
4.	jupyter notebook Ultrasound_Image_Reconstruction_UNet_Vs_VisionTransformer.ipynb
5.	Follow the instructions in the notebook to preprocess the data, train the models, and evaluate their performance.
Dataset
Due to size constraints, the dataset is not included in this repository. Training Data: https:/zenodo.org/records/7813791 and Testing Data: https://www.creatis.insa-lyon.fr/Challenge/IEEE_IUS_2016/home
Results
Preliminary results demonstrate the following:
•	U-Net excels in capturing fine-grained details in ultrasound images.
•	Vision Transformer provides competitive results, especially in scenarios requiring a global contextual understanding.
Detailed performance metrics and reconstructed image samples are available in the results/ folder 

