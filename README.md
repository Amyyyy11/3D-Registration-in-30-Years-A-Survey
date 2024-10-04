# 3D Registration in 30 Years: A Survey 
This is the official repository of **3D Registration in 30 Years：ASurvey (IEEE TPAMI)**, a comprehensive survey of recent progress in 3D registration for point clouds. For details, please refer to:

**3D Registration in 30 Years: A Survey**
## 1 Introduction
3D point clouds to a unified coordinate system, known as 3D point cloud registration, is a fundamental problem in numerous areas such as computer vision, computer graphics, robotics, and remote sensing.
## 2 Background
### 2.1 Basic Concepts
### 2.2 Datasets
### 2.3 Metrics

## 3 Pairwise Registration
### 3.1 Introduction

### 3.2 Pairwise Coarse Registration

#### 3.2.1 Geometric methods
In correspondence-based methods, a crucial step is the generation of correspondences, which plays a key role in determining the accuracy and robustness of the registration process.

##### 3.2.1.1 Correspondence-based Methods
###### 3.2.1.1.1 Correspondence Generation
**(1) Keypoint detection.**

**(2) Descriptors.**

**(3) Matching technique.**
###### 3.2.1.1.2 Correspondence Optimization
**(1) Voting-based methods.**

**(2) Voting-free methods.**

###### 3.2.1.1.3 Transformation Estimation
**(1) Sample-based methods.**

**(2) Parameter searching-based methods.**

##### 3.2.1.2 Correspondence-free Methods

#### 3.2.2 Deep-learning-based methods

##### 3.2.2.1 Supervised Methods

###### 3.2.2.1.1 Non End-To-End

**(1) Descriptor**

**(2) Others**

###### 3.2.2.1.2 End to End

**(1) PointNet-based**

**(2) Graph-based**

**(3) ConvNet-based**

**(4) Transformer-based**

##### 3.2.2.2 Unsupervised Methods

**(1) Self Reconstruction**

**(2) Mutual Reconstruction**

**(3) Metric Learning**

**(4) Regstration Prior**

**(5) Iteratively Registration**

### 3.3 Pairwise Fine Registration

#### 3.3.1 ICP and its variants

##### 3.3.1.1 Selection of Points

##### 3.3.1.2 Matching Points

##### 3.3.1.3 Weighting of Pairs

##### 3.3.1.4 Rejecting Pairs

##### 3.3.1.5 Error Metric and Minimization

#### 3.3.2 others

## 4 Multi-view Registration

### 4.1 Multi-view Coarse Registration

Multi-view coarse registration aims to align point clouds from multiple views to form a coherent global model. 

#### 4.1.1  Geometric methods

##### (1) **Corresspondence**

##### (2) connected graph

#### 4.1.2  Learning-based methods

##### (1)End-to-end

##### (2)Feature Descriptors

##### (3)Self-Supervised and Unsupervised

##### (4)Others

## 5 Other Registration Problems 
### 5.1 Cross-scale Registration 
#### 5.1.1 Traditional ICP-like methods 

#### 5.1.2 Deep-learning methods 

### 5.2 Cross-source Registration 
#### 5.2.1 Conventional Optimization methods 

#### 5.2.2 Deep Neural Network methods 

### 5.3 Color Point Cloud Registration 

### 5.4 Multi-instance Point Cloud Registration 
#### 5.4.1 Multi-model Fitting methods 

#### 5.4.2 PPF-like methods 

### 5.5 Sim2Real Registration 
