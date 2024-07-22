## Introduction
This project focuses on developing an integrated multitask learning framework to identify users potentially suffering from depression on online social networks. By leveraging various data modalities such as text, images, and social behavior, the framework aims to improve the accuracy and precision of depression detection.

## Problem Statement
Depression is a critical mental health issue that can significantly impact individuals' lives. Early detection through social media can help in timely intervention and support. This project addresses the challenge of accurately detecting signs of depression from user-generated content on social networks.

## Dataset
The project utilizes the WU3D dataset, a heterogeneous user-generated dataset specifically curated for this research. It includes diverse data types from the Sina Weibo platform, including textual content, images, and behavioral data.
Link: https://www.kaggle.com/datasets/webifier/wu3d-dipression-detection

## Categories
The project categorizes features into three main types:
- **Text Features**: Analyzed using XLNet for capturing nuanced depression-related signals.
- **Image Features**: Processed using CNN & Bi-GRU to identify visual patterns indicative of depression.
- **Social Behavior Features**: Assessed using XLNet to understand user interaction patterns and posting behaviors.

## Model
The proposed model is an integrated multitask learning framework that combines different data modalities:
- **Text Analysis**: XLNet
- **Image Analysis**: CNN & Bi-GRU
- **Behavioral Analysis**: XLNet

## Steps
1. **Data Preprocessing**: Cleaning and preparing the dataset for analysis.
2. **Feature Extraction**: Utilizing XLNet, CNN, and Bi-GRU for extracting relevant features from text, images, and social behavior.
3. **Model Training**: Training the multitask learning model on the processed dataset.
4. **Evaluation**: Assessing the model's performance using accuracy and precision metrics.

## Outcomes
- **Accuracy**: The model achieved an accuracy of 95%, demonstrating its reliability in detecting depression.
- **Precision**: The model attained a precision of 93%, ensuring that the identified cases are true positives.

## Conclusion
The integrated multitask learning framework effectively combines text, images, and social behavior to enhance the detection of depression on social networks. The high accuracy and precision metrics underscore the model's potential for real-world applications.

## How to Use
1. Clone the repository.
2. Navigate to the project directory: `cd your-repo-name`
3. Install the required dependencies: `pip install -r requirements.txt`
4. Run the preprocessing script: `python preprocess.py`
5. Train the model: `python train_model.py`
6. Evaluate the model: `python evaluate_model.py`

## Future Work
Future research will focus on further examining the attributes and behavioral samples of individuals experiencing depression to propose more positively characteristic-driven solutions for personalized depression identification in online social networks.
