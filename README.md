# Deep Learning Homework - Charity Data

## Purpose

The purpose of this module was to determine the accuracy of deep learning models (i.e., neural networks) designed to predict whether a charitable organization would be "successful" if funded. 

## Data

A non-profit foundation, Alphabet Soup, provided a CSV file containing more than 34,000 organizations that received funding over the years. The data file consisted of 9-relevant features and 1 outcome (Is_Successful).

## Steps

*  Preprocess the data
*  Compile, train, and evaluate the model
*  Optimize the model

## Results

We computed a total of 4 deep learning models. The best model had an accuracy of 0.73 and loss of 0.587

Model # 1 specs



Model # 1 accuracy and loss



Model # 2 specs



Model # 2 accuracy and loss




Model # 3 specs



Model # 3 accuracy and loss




Model # 4 specs



Model # 4 accuracy and loss


#  Conclusion

Accuracy of the models ranged from 0.729 to 0.73 with the best accuracy being observed among model 3. Despite adding an additional hidden layer, model accuracy improved, but not significant enough to warrant discussion. We explored tuning the model, but gave up after 1.5 hours.  Perhaps the model warrents additional pre-processing such as creating more bins for CLASSIFICATION and APPLICATION_TYPE would yield better model performance.  Alternatively, suffient time and computational power to tune the model and potentially more features could possibly enhance model performance.  