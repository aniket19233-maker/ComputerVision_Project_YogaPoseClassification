# Computer Vision Project YogaPoseClassification
This was a Computer Vision Project which classified Yoga Poses using Features Extracted From Custom Features Created.


# CSE 544 Computer Vision Project

## Yoga Pose Classification using Custom Features and Machine Learning (T-1)

#### Work done as a part of the course CSE 544: Machine Learning by Prof. Koteshwar Rao JerriPothula.

## About the Project

#### In this Project, we present a method to classify and score six yoga poses - Tree Pose, Warrior-2 Pose, Goddess Pose, Triangle Pose, Extended Side Angle Pose, and Dancer Poseby designing custom features from human pose key-points. Real life instruction for a large number of poses involves emphasis on angle, the shape that is being formed and the ratio of distances between body parts. To evaluate the effectiveness of our proposed features, we create a dataset for the six poses and apply ML techniques on the feature data extracted from them. The predictions are evaluated using metrics such as accuracy and F1-score and the yoga pose is scored using cosine similarity which can be used as a corrective measure by a self-learner.

#### we performed Yoga Pose Classification using self designed custom features extracted using key points obtained from a key point detector - mediaPipe. Our results are proven to be better than those given in the YOGA-82 Dataset Paper.

## DataSet
#### [DataSet](https://drive.google.com/drive/folders/132OOTGoOD52bpGTQUeCLXDeO__KI0_gP?usp=sharing)

#### The dataset used in the Yoga - 82 dataset paper.

![DataSet Description](https://github.com/RahulSethi070801/ML_Project/blob/main/DataSet/Description.PNG?raw=true "DataSet Description")

## Feature Extraction
#### All the keypoints obtained using media pipe helped us create the custom features 
![Feature/Keypoints Exraction](https://github.com/aniket19233-maker/ComputerVision_Project_YogaPoseClassification/blob/main/Methodology-Pipeline/mediapipe_extracted_features.png)


## Methodology 
#### We performed various ML methods and did analysis of results obtained by our custom designed features and raw features obtained from media-pipe and also from the Yoga-82 dataset paper. 

![Pipeline](https://github.com/aniket19233-maker/ComputerVision_Project_YogaPoseClassification/blob/main/Methodology-Pipeline/Work-Flow-Pipeline%20of%20our%20model.png  "Pipeline")


![Pose-Correction Pipeline](https://github.com/aniket19233-maker/ComputerVision_Project_YogaPoseClassification/blob/main/Methodology-Pipeline/pose-correction-pipeline.png "Pose-Correction Pipeline")

## Running the Code

#### Download the entire repository and extract all the files to a folder.<br> There is a python notebook which can be run to see the results mentioned in the [Report](https://github.com/aniket19233 maker/ComputerVision_Project_YogaPoseClassification/blob/main/Report/CV_Project_Report.pdf). 

#### Code for Implementation : - <br> [KeyPoint Extraction + Custom Features + Training](https://github.com/RahulSethi070801/ML_Project/blob/main/ml_project_oversampled.ipynb) <br> 

## Results and Analysis
#### Refer to [Report](https://github.com/aniket19233-maker/ComputerVision_Project_YogaPoseClassification/blob/main/Report/CV_Project_Report.pdf) for results and analysis(tables included)


## Contributors
- Aniket Verma (2019233)
- Hardik Garg (2019040)
- Tarini Sharma (2019450)
