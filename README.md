# Deep Learning Homework - Charity Data

## Purpose

The purpose of this module was to determine the accuracy of deep learning models (i.e., neural networks) designed to predict whether a charitable organization would be "successful" if funded. 

## Data

A non-profit foundation, Alphabet Soup, provided a CSV file containing more than 34,000 organizations that received funding over the years. The data file consisted of 9-relevant features and 1 outcome (Is_Successful).

### Tools

**  Google Collab notebook
**  Modules: tensorflow, Keras-tuner, sklearn, 

## Steps

*  Preprocess the data
*  Compile, train, and evaluate the model
*  Optimize the model

## Results

We computed a total of 4 deep learning models. The best model had an accuracy of 0.73 and loss of 0.587

### Model # 1 specs

![image](https://user-images.githubusercontent.com/82011523/141741353-708da506-c864-4e1b-9bf0-d10fce9fcf95.png)


### Model # 1 accuracy and loss

![image](https://user-images.githubusercontent.com/82011523/141741438-88635f69-b146-4b5c-ad62-4e6cf52fc467.png)


### Model # 2 specs

![image](https://user-images.githubusercontent.com/82011523/141741498-b527299c-60a6-4a98-b0da-78e4b4eef400.png)


### Model # 2 accuracy and loss

![image](https://user-images.githubusercontent.com/82011523/141741559-54ef9832-66c7-4c8e-af3a-6c8aa602fa17.png)


### Model # 3 specs

![image](https://user-images.githubusercontent.com/82011523/141741645-225420a8-a328-4480-8b82-7ee08a637372.png)


### Model # 3 accuracy and loss

![image](https://user-images.githubusercontent.com/82011523/141741716-bd1124ae-7f2b-4749-85cf-7fa4c76d8fdf.png)


### Model # 4 specs

![image](https://user-images.githubusercontent.com/82011523/141741775-b7fb21c7-52ed-4e25-8385-5246deb766a4.png)


### Model # 4 accuracy and loss

![image](https://user-images.githubusercontent.com/82011523/141741878-89ac2559-6100-4cc7-a386-3fa4c11e9bfd.png)


#  Conclusion

Accuracy of the models ranged from 0.728 to 0.730 with the best accuracy being observed among model 3. Despite adding an additional hidden layer, model accuracy improved, but not significant enough to warrant discussion. We explored tuning the model, but gave up after 1.5 hours.  Perhaps the model warrents additional pre-processing such as creating more bins for CLASSIFICATION and APPLICATION_TYPE would yield better model performance.  Alternatively, suffient time and computational power to tune the model and potentially more features could possibly enhance model performance.  
