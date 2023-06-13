# FakeBillDetection

This project leverages the principles of big data analysis to develop a user-friendly website for users to verify the 
authenticity of their bills.

The dataset utilized in this project is sourced from [Kaggle](https://www.kaggle.com/datasets/alexandrepetit881234/fake-bills), a dataset library resource. 

The dataset comprises 15,000 rows, divided into two equal halves. The first half was employed to create and train a robust logistic regression model capable of accurately predicting whether a bill is genuine or counterfeit.

Careful consideration was given to selecting predictor variables based on their significance in determining the authenticity of a bill.

Subsequently, the second half of the dataset was employed as a test dataset to evaluate the model's performance, resulting in an exceptional accuracy rate of 99.5%. A PKL file encapsulating the trained model's state was generated for deployment on a dedicated website, enabling users to access its capabilities.

## How the Logistic Regression model is generated
To gain insight into the process of generating the logistic regression model, you can watch the following video:
[![Alt text for your video](https://img.youtube.com/vi/QL7LXAvn-Go/0.jpg)](https://www.youtube.com/watch?v=QL7LXAvn-Go)

<span style="font-size: 25px;">[See the model in action!](https://www.kaggle.com/datasets/alexandrepetit881234/fake-bills)</span>
