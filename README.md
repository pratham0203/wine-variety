# wine-variety
## Contents of the Project:-
#### 1) Model used : SVM and Decision Tree (Classification)
![Capture4](https://user-images.githubusercontent.com/20925116/81508883-79cff900-9324-11ea-8924-86f8e08f323b.PNG)
![Capture5](https://user-images.githubusercontent.com/20925116/81508882-79376280-9324-11ea-9905-378639ba332a.PNG)
#### 2) Features extracted:(price,points)
![Capture11](https://user-images.githubusercontent.com/20925116/81508935-cb788380-9324-11ea-8e5a-21adea9e31a2.PNG)![Capture11](https://user-images.githubusercontent.com/20925116/81508935-cb788380-9324-11ea-8e5a-21adea9e31a2.PNG)
#### 3) Model Accuracy in Train:(accuracy_score =0.72216,f1_score = 0.6627)
![Capture6](https://user-images.githubusercontent.com/20925116/81508809-06c68280-9324-11ea-8200-814ef4791a79.PNG)
![Capture7](https://user-images.githubusercontent.com/20925116/81508806-04642880-9324-11ea-97bc-3d7383080e14.PNG)

### 1)Sample Vector Machine integrated with Decision Tree (Main Project):
Here using Classification models that uses a data train.csv to train itself and then classify the vine variety based on important usable features.The variety of the vine can then be predicted using the trained and tested model. After passing the test data the model predicts the output and writes the output in test.csv where each variety has been assigned a unique numerical value:

![Capture](https://user-images.githubusercontent.com/20925116/81508395-87d04a80-9321-11ea-8309-f8d7c4779bea.PNG)

Further since the dataset required cleaning some features where dropped for convienience.
The file includes these data for evaluation:

![Capture3](https://user-images.githubusercontent.com/20925116/81508660-0083d680-9323-11ea-8eb0-8277d0b18628.PNG)




Later on after using the SVM and the Classification model is created.



For this the data like number of tokens, number of shares etc are used from the respected website.

Later on the virality or popularity score is given:



The score lies between 0 and 1(0 corresponding to not popular news and 1 corresponds for popular news)


### 2)Classification Model:
This model has various algos like Logistics Regression,Random Forest Classifier,SVM but the one actively used is RandomForestClassifier due to its best results.


The Output shows Essentials of the model using RandomForestClassifier after being trained and tested.




The Output shows the labels before and after standardization.
It also shows the accuracy of this model.



### 3)Regression Model:
This model uses Bayesian Linear Regression to solve the problem and give us the required accuracy of the model. 
### 4)News Aggregator(made using Django by scraping popular websites like Times of India etc):

I also made a website using Django that can be later used to project the popular news on a single site only.
![website](https://user-images.githubusercontent.com/20925116/80413115-944daf80-88ec-11ea-83ed-a0e037194788.PNG)


Web Scraping of Times Of India:
![webscraptoi](https://user-images.githubusercontent.com/20925116/80413138-9b74bd80-88ec-11ea-86b9-c2931bb6e418.PNG)


Web Scraping Of Hindustan TImes:
![webscrapht](https://user-images.githubusercontent.com/20925116/80413137-9adc2700-88ec-11ea-90c6-c4be970a6f72.PNG)


Web Scraping of The Economist:
![webscrapet](https://user-images.githubusercontent.com/20925116/80413131-99126380-88ec-11ea-92ba-0f263fb3ff5e.PNG)




## Future of the Project:
A much proper integration of model and NewsAggregator which could predict the virality of the news and display the link to the site on my website asap.
## License
The project is available as open source under the terms of the MIT License.
