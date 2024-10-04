# 3D Registration in 30 Years: A Survey 
This is the official repository of **3D Registration in 30 Years：ASurvey (IEEE TPAMI)**, a comprehensive survey of recent progress in 3D registration for point clouds. For details, please refer to:

**3D Registration in 30 Years: A Survey**
## 1 Introduction
3D point clouds to a unified coordinate system, known as 3D point cloud registration, is a fundamental problem in numerous areas such as computer vision, computer graphics, robotics, and remote sensing.
## 2 Pairwise Registration
### 2.1 Introduction

### 2.2 Pairwise Coarse Registration

#### 2.2.1 Geometric methods
In correspondence-based methods, a crucial step is the generation of correspondences, which plays a key role in determining the accuracy and robustness of the registration process.

##### 2.2.1.1 Correspondence-based Methods
###### 2.2.1.1.1 Correspondence Generation
**(1) Keypoint detection.**

**(2) Descriptors.**

**(3) Matching technique.**
###### 2.2.1.1.2 Correspondence Optimization
**(1) Voting-based methods.**

**(2) Voting-free methods.**

###### 2.2.1.1.3 Transformation Estimation
**(1) Sample-based methods.**

**(2) Parameter searching-based methods.**

##### 2.2.1.2 Correspondence-free Methods

#### 2.2.2 Deep-learning-based methods

##### 2.2.2.1 Supervised Methods

###### 2.2.2.1.1 Non End-To-End

**(1) Descriptor**

**(2) Others**

###### 2.2.2.1.2 End to End

**(1) PointNet-based**

**(2) Graph-based**

**(3) ConvNet-based**

**(4) Transformer-based**

##### 2.2.2.2 Unsupervised Methods

**(1) Self Reconstruction**

**(2) Mutual Reconstruction**

**(3) Metric Learning**

**(4) Regstration Prior**

**(5) Iteratively Registration**

## 4 Other Registration Problems 
### 4.1 Cross-scale Registration 
#### 4.1.1 Traditional ICP-like methods 
  
#### 4.1.2 Deep-learning methods 
  
### 4.2 Cross-source Registration 
#### 4.2.1 Conventional Optimization methods 
  
#### 4.2.2 Deep Neural Network methods 
  
### 4.3 Color Point Cloud Registration 
  
### 4.4 Multi-instance Point Cloud Registration 
#### 4.4.1 Multi-model Fitting methods 
  
#### 4.4.2 PPF-like methods 
  
### 4.5 Sim2Real Registration 
