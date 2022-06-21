# Computer Vision Project YogaPoseClassification
This was a Computer Vision Project which classified Yoga Poses using Features Extracted From Custom Features Created.


# CSE 544 Machine Learning Project

## Rainfall Prediction using Machine Learning (T-28)

#### Work done as a part of the course CSE 544: Machine Learning by Prof. Koteshwar Rao JerriPothula.

## About the Project

#### In this Project, we present a method to classify and score six yoga poses - Tree Pose, Warrior-2 Pose, Goddess Pose, Triangle Pose, Extended Side Angle Pose, and Dancer Poseby designing custom features from human pose key-points. Real life instruction for a large number of poses involves emphasis on angle, the shape that is being formed and the ratio of distances between body parts. To evaluate the effectiveness of our proposed features, we create a dataset for the six poses and apply ML techniques on the feature data extracted from them. The predictions are evaluated using metrics such as accuracy and F1-score and the yoga pose is scored using cosine similarity which can be used as a corrective measure by a self-learner.

#### we performed Yoga Pose Classification using self designed custom features extracted using key points obtained from a key point detector - mediaPipe. Our results are proven to be better than those given in the YOGA-82 Dataset Paper.

## DataSet
#### [DataSet](https://drive.google.com/drive/folders/132OOTGoOD52bpGTQUeCLXDeO__KI0_gP?usp=sharing)

#### The dataset used in the Yoga - 82 dataset paper.

![DataSet Description](https://github.com/RahulSethi070801/ML_Project/blob/main/DataSet/Description.PNG?raw=true "DataSet Description")

## Feature Extraction
#### All the keypoints obtained using media pipe helped us create the custom features [Feature/Keypoints Exraction](https://github.com/RahulSethi070801/ML_Project/tree/main/EDA%2BPreprocessing)


## Methodology 
#### We performed various ML methods and did analysis for both Oversampled and Undersampled dataset done through sklearn library.

![Pipeline](https://github.com/aniket19233-maker/ComputerVision_Project_YogaPoseClassification/blob/main/Methodology-Pipeline/Work-Flow-Pipeline%20of%20our%20model.png  "Pipeline")

![Pose-Correction Pipeline](https://github.com/aniket19233-maker/ComputerVision_Project_YogaPoseClassification/blob/main/Methodology-Pipeline/Work-Flow-Pipeline%20of%20our%20model.png)

## Running the Code

#### Download the entire repository and extract all the files to a folder.<br> There are 2 python notebooks, one for Oversampled data and another for Undersampled data.<br> They can be run using 'Run All' command in the respective IDE.

#### Code for both parts : - <br> [Oversampled](https://github.com/RahulSethi070801/ML_Project/blob/main/ml_project_oversampled.ipynb) <br> [Undersampled](https://github.com/RahulSethi070801/ML_Project/blob/main/ml_project_undersampled.ipynb)

## Results and Analysis
#### Refer to [Report_28](https://github.com/RahulSethi070801/ML_Project/blob/main/Report_T28.pdf) for results and analysis(tables included)
#### All the plots for results are added in the folder [Results](https://github.com/RahulSethi070801/ML_Project/tree/main/Results)


## Contributors
- Aniket Verma (2019233)
- Hardik Garg (2019040)
- Tarini Sharma (2019450)
