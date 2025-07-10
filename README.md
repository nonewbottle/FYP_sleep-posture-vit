# Sleep Posture Recognition using Transfer Learning and Pretrained Models

## 1. Source Code Repository  
The full source code for this project is hosted on GitHub:  
https://github.com/nonewbottle/FYP_sleep-posture-vit

## 2. Tools & Environment Setup  
- **Python Version**: Python 3.10  
- **Development Environment**: Jupyter Notebook  
- **Recommended Platform**: Kaggle Notebooks – for free access to GPU without local setup  
- **Library Installation**:  
* Use the following command to install required libraries if running locally:
```
pip install -r requirements.txt
```
- **Hardware Requirements**:  
* GPU (NVIDIA preferred) for training  
* Platforms: Google Colab, Kaggle Notebook, or local CUDA-enabled machine

## 3. Dataset  
- **Name**: Simultaneously-collected multimodal Lying Pose (SLP) dataset  
- **Modality Used**: RGB  
- **Access Instructions**:  
* This dataset requires access permission from the ACLab.  
* Please request access and download the dataset from the official SLP page:  
  https://ostadabbas.sites.northeastern.edu/slp-dataset-for-multimodal-in-bed-pose-estimation-3/

## 4. How to Run  

### Option A: Run on Kaggle (Recommended)  
- Upload the notebook and dataset to https://www.kaggle.com/code  
- Kindly change the dataset path manually in the notebook to match the uploaded location (e.g., `/kaggle/input/your-dataset-name`)  
- Make sure to set the runtime to GPU in Settings  
- Execute each cell sequentially  
- No setup required—Kaggle pre-installs most libraries  

### Option B: Run Locally  
- Clone the repo:
```
git clone https://github.com/nonewbottle/FYP_sleep-posture-vit.git
cd FYP_sleep-posture-vit
```
- Install the required libraries:
```
pip install -r requirements.txt
```
- Kindly update the dataset path variable in the notebook to your local dataset directory  
- Open the Jupyter Notebook:
```
jupyter notebook
```
- Run the notebook cell by cell
