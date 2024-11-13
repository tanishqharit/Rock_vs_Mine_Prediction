# Rock vs Mine Prediction Using Submarine Sonar Data

Sonar data in a CSV file undergoes preprocessing to prepare it for model training. The processed data is then split into training and testing sets. A Logistic Regression model is built and trained using the training data, and the model is subsequently tested on new data for prediction.

<img src="https://github.com/tanishqharit/Rock_vs_Mine_Prediction/blob/main/Work_Flow.png" alt="Workflow Diagram" width="500"/>

### Authors

- [Tanishq Harit](https://github.com/tanishqharit)
- [Siddhardhan (Creator)](https://github.com/siddhardhan23)


### DataSet

The Dataset has been taken from [UC Irvine Machine Learning Repository](https://archive.ics.uci.edu). This dataset contains patterns obtained by bouncing sonar signals off a metal cylinder and rocks at various angles and conditions. The data set contains signals obtained from a variety of different aspect angles, spanning 90 degrees for the cylinder and 180 degrees for the rock. The Last column in this dataset indicates that, whether it's a mine or a rock, which is useful while making prediction model.

DataSet is included in the repository by the name "Sonar_Dataset.csv".

[DataSet Link](https://archive.ics.uci.edu/dataset/151/connectionist+bench+sonar+mines+vs+rocks)

### Libraries and Tools

**Libraries:** Numpy, Pandas, Scikit-Learn

**Model:** Logistic Regression

**Tool:** Google Colaboratory


### Lessons Learned

This is my first machine learning project which is done entirely on Google Colaboratory. During the build I learned how to read CSV file from Google Drive and loading that to a Pandas dataframe, seprating data and label, training & testing data using train_test_split, model training using Logistic Regression, accuracy on training & test data, finally predicting the result by pushing new data into the model.


### Acknowledgements

- [Project Youtube Link](https://www.youtube.com/watch?v=fiz1ORTBGpY)
- [Project Github Link](https://github.com/siddhardhan23/Complete-Machine-Learning-Course-Part-1/blob/main/ML%20Use%20Case%201.%20Rock_vs_Mine_Prediction.ipynb)
