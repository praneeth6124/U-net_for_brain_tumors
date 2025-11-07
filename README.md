# Brain Tumor Segmentation using UNet on MRI Scans

*Project Overview:*  
handcrafted a *UNet-based deep learning model* for *automated segmentation of brain tumors* from grayscale MRI scans. The model achieves a *Dice score of ~0.50* using a combination of *BCEWithLogitsLoss and Dice Loss* along with data augmentation.  

The project includes a complete pipeline for *training, evaluation, and visualization* of predictions, serving as a foundation for advanced *medical image segmentation tasks*.

*Key Features:*  
- Grayscale MRI brain tumor segmentation using UNet  
- Dice score evaluation for quantitative performance  
- Data augmentation including flips, rotations, and affine transformations  
- Early stopping and checkpoint saving for optimal training  
- Visualization of predicted vs. ground truth masks

*Dataset:*  
- Brain Tumor Segmentation Dataset by Nikhil Tomar (2D MRI images with masks)  

*Technologies & Libraries:*  
- Python, PyTorch, torchvision, PIL, matplotlib, scikit-learn  

*Usage:*  
1. Clone this repository  
```bash
git clone https://github.com/your-username/Brain-MRI-Segmentation.git
