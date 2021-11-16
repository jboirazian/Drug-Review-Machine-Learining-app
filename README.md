
# Medical Drug Review Machine Learning Analyzer app

Application developed during the Digital House Data Science 2021 course 

This app extracts tweets and post from Reddit using their respective APIs , runs an analysis using a LGBM model trained with this dataset:

https://www.kaggle.com/jessicali9530/kuc-hackathon-winter-2018

and gives statistics about the Medical drug in that social media site.

Database contains **161297** reviews.



## Example 1:

During the COVID-19 pandemic a really popular medication is the Dexamethasone , specially for patients in critical condition.

In this example we run the app for this drug and searching in Reddit´s r/all ( a subreddit with the most popular posts from multiple subreddits)

![alt text](https://github.com/jboirazian/Drug-Review-Machine-Learning-app/blob/main/images/11-9-2021%2014.9.16%201.jpg)

After running the model this are our final results:

![alt_text](https://github.com/jboirazian/Drug-Review-Machine-Learning-app/blob/main/images/newplot%20(34).png)

![alt-text](https://github.com/jboirazian/Drug-Review-Machine-Learning-app/blob/main/images/newplot%20(33).png)

As we can see there is a spike of interest during the firsts months of 2020 , when the pandemic started.

We also generate a Wordcloud of all the collected posts.

![alt-text](https://github.com/jboirazian/Medical-Drug-Review-Machine-Learning-app/blob/main/images/2678d923e9c4519bb72e56b315be37ae97ae463c609b6bc58ff16709%20(1).jpeg)

## Example 2:

Adderall is a drug that is commonly used to treat Attention-Deficit/Hyperactivity Disorder (ADHD). There is a subreddit (r/adhd) were many people with this medical condition talk about this and many others medications used for the treatment.

![alt-text](https://github.com/jboirazian/Medical-Drug-Review-Machine-Learning-app/blob/main/images/11-9-2021%2016.9.27%201.jpg)

![alt-text](https://github.com/jboirazian/Medical-Drug-Review-Machine-Learning-app/blob/main/images/newplot%20(35).png)

![alt-text](https://github.com/jboirazian/Medical-Drug-Review-Machine-Learning-app/blob/main/images/newplot%20(36).png)

![alt-text](https://github.com/jboirazian/Medical-Drug-Review-Machine-Learning-app/blob/main/images/75eda44ec38f1ab9f41a1124e21135c1df9ae9da0faf3c46224e9d8e.jpeg)


#### Link to the app hosted in Heroku:  https://tinyurl.com/DrugReviewAnalyzer

Grupo 6 - TP 4 - Digital House - Data Science

### Members: 

Juan Boirazian : juanboirazian@gmail.com

Jorge Corro : jorgeccv1224@gmail.com

Federico Vessuri : fvessuri@gmail.com

Mariana peinado: peinadomariana@gmail.com

Franco Visintini: francovisintini@gmail.com

##### Visitors: 
![Visitor Count](https://profile-counter.glitch.me/{jboirazian}/count.svg)
