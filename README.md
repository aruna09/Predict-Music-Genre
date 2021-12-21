# Predict-Music-Genre ☜(ﾟヮﾟ☜)

## Problem Statement👩‍🏫
Given a list of features from a song/music, classify it as any one of the target categories.

## Tools used ⚙

**Language**: python 3.x

**Editor**: google colab

**Visualizations**: matplotlib, seaborn

**ML Library**: scikit learn

## How did I start?👩

### Loading the data ofcourse!

![image](https://user-images.githubusercontent.com/25157152/146932081-2440eb59-6753-4e2a-9b70-4547a23baeb7.png)


### Observation🔎: 
A little observation reveals pretty straight forward float features and a couple of categorical values(note: these will need some kind of conversion to be used for training)

![image](https://user-images.githubusercontent.com/25157152/146930128-3c83d984-7cd3-44ca-9741-2fafd09e930d.png)

  ![image](https://user-images.githubusercontent.com/25157152/146930043-a62007cd-3c9e-4ccc-b963-f35012843fd8.png)


### Visualization📊: 
Time for some cool graphs!

![image](https://user-images.githubusercontent.com/25157152/146930853-46c6e3e7-4509-4abd-8340-349c94373d1c.png)


### Actual Coding begins👩‍💻: 

1. Drop **insignificant columns** like (any kind of id's or names)
2. Check for **null values/special characters** that will need trasformation
    
   ![image](https://user-images.githubusercontent.com/25157152/146929714-531352f9-8326-4bde-8d97-b017f28527ab.png)
         
 3. **Preprocessing**:
    
![image](https://user-images.githubusercontent.com/25157152/146932941-88b3e974-95ab-4f54-999b-9002a8d9bf2f.png)
 
 
![image](https://user-images.githubusercontent.com/25157152/146932995-0a7c9a9f-c7fc-45d4-91ae-9dc3e7fe09a9.png)


![image](https://user-images.githubusercontent.com/25157152/146933076-264f9799-4450-4d6e-86ec-b7ed479a7463.png)

### Model Building👩‍🏫

This is where we start building our classifiers which will be trained on this super clean data!

### Prediction📓

Its show time!! Check the code to find which classifier performed the best!

