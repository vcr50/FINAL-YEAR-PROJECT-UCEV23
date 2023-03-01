# FINAL-YEAR-PROJECT-UCEV2023
ANNA UNIVERSITY, Final Year Project-This Repository Is used for Demonstrating and Team Collaboration

## __Team Size : 3__


|Team Leader :| VIJAY R |
| ------------|---------------|  
|Team member 1 :|MANOJKUMAR G|
|Team member 2:|MOHAMED MUSTHAPA N|


# Project Name :<b> Interpretable Uncertainty-aware Robust Detection of Diabetic Retinopathy Severity using Deep Context Knowledge Transfer Learning</b>

# Retinal Blindness (Diabetic Retinopathy) detection   

# Problem statement :    
Diabetic Retinopathy is a disease with an increasing prevalence and the main cause of blindness among the working-age population. The risk of severe vision loss can be significantly reduced by timely diagnosis and treatment. Systematic screening for DR has been identified as a cost-effective way to save health services resources. Automatic retinal image analysis is emerging as an important screening tool for early DR detection, which can reduce the workload associated to manually grading, as well as safe diagnosis costs and time. Many research efforts in the last years have been devoted to developing automated tools to help in the detection and evaluation of DR lesions.
We are interested in automating this predition using deep learning models.

# Dataset : [APOTS Kaggle Blindness dataset](https://www.kaggle.com/c/aptos2019-blindness-detection)      

# Solution :   
I am proposing Deep Context Knowledge Transfer Learning classification technique using CNN pretrained model
This is a collaborative project of a team of three where my main work is on developing, training and testing various CNN models along with some secondary work.
Deep Context Knowledge Transfer Learning looks promising because already various types of image classification tasks has been performed by various CNN's so, we can rely on DL pretrained models, or we can modify some layers if we wish to :)    
A GUI based system has been made using Tkinter and used heidiSQL to maintain and store a list of predictions with their patient id and name (which is very risky , the reason we will get to it some time later).   

# Summary of Technologies used in this project :       
| Dev Env. | Framework/ library/ languages |
| ------------- | ------------- |
| Backend development  | PyTorch (Deep learning framework) |
| Frontend development | Tkinter (Python GUI toolkit) |
| Database connectivity | HeidiSQL (MySQL server) |
| Programming Languages | Python, SQL |
#Hardware Requirements
Processor: Minimum i3 Dual Core
Ethernet connection (LAN) OR a wireless adapter (Wi-Fi)
Hard Drive: Minimum 100 GB; Recommended 200 GB or more
Memory (RAM): Minimum 8 GB; Recommended 32 GB or above

# Software Requirements
| Python |
| Anaconda |
| Jupyter Notebook |
| TensorFlow |
Keras    

# Data visualization :     
Input data (raw) is like this -     

# Resnet152 model summary :     
I have only shown below the main layers of Residual Network (ResNet) and each of the 'layer1', 'layer2', 'layer3' and 'layer4' contains various more layers.      
 

# Visualization of complete system :    
 


# Getting started :       

 
 # Future Prospect :  
 In future, in order to further increase the accuracy of early-stage, we plan to train specific models for specific stages
 and then ensemble the outcome in order to increase the accuracy of early stages
 
 * My next goal is to develop this into Web App (probably using some lightweight model, as Residual Network (ResNet)  models are heavy).   
 * Next goal will be using encryption techniques to achieve not only high accuracy but also high level of privacy in terms of differentially private basis and use techniques such as Federated learning and Secure Multi party computation for privacy preserving deep learning classification.
 
 * Achieving a level of privacy is also very important task in medical datasets so that there can be factor of trust established between different stakeholders using  
   the system.   
 * Some ideas for concurrency control has to be implemented properly using some kind of locks defined in MySQL so that multiple users can use the system at the same  
   time when deployed on web.
 (Otherwise, locally you can run the executable file multiple times to open and run the GUI and it works fine).      
 * Reducing TYPE-II error (false negatives) as this metric is really useful in Healthcare domain.   

[Note : The training files in this repo is only shown after final training, as it took around more than 100 epochs to reach 97% accuracy and a lot of compute power and time.]     


⭐️ this Project if you liked it !
