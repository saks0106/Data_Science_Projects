
# KickerStarter Funding Project

Kickstarter Projects is a platform where Entrepreneurs can post their projects or business ideas and try and get funded from other people.



**Understanding the KickerStarter features and columns**:

    1.**ID**: ID number is unique identifier
    2.**Name**: Name is the name of the projects to get funded
    3.**Category**: A high level overview of project Genre
    4.**Subcategory**: More specific details of Category
    5.**Country**: Which country the KickStarter projects belongs to
    6.**Lauched**: Date when the project was launched
    7.**Deadline**: End date when the project should get funded
    8.**Goal**: Amount required to get the project Successful
    9.**Pledged**: Amount that the project actually received
    10.**Backers**: How many people have actually supported the project 

 - [Project CSV File](https://drive.google.com/file/d/1vLVc3BH-7nhB-MreqhVrlepRGTRRhArj/view?usp=sharing)




## Tech Stack

This project requires Python and the following Python libraries installed:

**Softwares:**  Jupyter Notebook || Google Colab

**Libraries:**  Pandas, Numpy, Matplotlib, SeaBorn, SciKit-Learn





## Acknowledgements

 - [Project DataSet- KickStarter](https://www.mavenanalytics.io/)

## Deployment

To Deploy the project, open Anaconda prompt or Google Colab and Open the project file ie KickerStarter_Project.ipynb.
Open the kickstarter_projects.csv file using Pandas



## Charts Descriptions

**Pie Chart**: The following pie chart reveals the state of KickStarter Projects. We can infer that failed projects contribute to more than half of all the states followed by Successful.
Great visual to know the count of certain parameters.

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/1.PNG)

**Bar Chart**: The bar chart is a count plot for the category column which reveals descending bars starting from Film&Video followed by Music and Publishing.
Great way to know most & least important values

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/Capture2.PNG))

**Crosstab Bar Graph**: The Bar Graph gives a nice insight of the level of State based on Every Category values. Again it reveals that Failed projects are in great number compare to rest of the states.

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/2.PNG)


**Count Bar Plot**: The count plot tells us that which country is leading in KickStarter Projects. Clearly United States dominates the market.

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/3.PNG)

**Line Graph**: The stacked line graphs tells us that during which years the Projects Goal Completion Ratio was the highest. 2016 was a great year to get KickStarter Projects funded.

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/4.PNG)

**Seaborn HeatMap**: Heat map is a great tool to know the correlation between different columns. 

    1.Values close to -1 have the negative correlation with the corresponding column. 
    2.Values close to 0 have the least correlation with the corresponding column.
    3.Values close to +1 have the highest  correlation with the corresponding column.

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/indejjx.png)

**Bar Stack Plot**: Using and Experimenting different Machine Learning Models is a great way to know which model works best for the given dataset. Except for Naive Bayes model, all 3 models gives a very good accuracy

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/5.PNG)

**ROC/AUC Curve**: The Receiver Operating Characteristic curve or ROC curve gives us a excellent indication of False positive rate(fpr) vs. True positive rate(tpr)
More the graph towards the X-axis, more the error values. In our case, it stands @ 99% which may prove that our model is **OVERFITTING** or our model has learned the feature patterns well

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/6.PNG)


**Confusion Matrix**: We want maximum values to lie @ the diagonal as it states True positive and True negative.

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/index.png)

**Cross Validation Bar Plot**: Combining the 4 Evaluation Metrics ie Accuracy, Precision, Recall, F1

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/Capture8.PNG)

**Bar Feature Importance Plot**: An Alternate graph for HeatMap in the form of bar graphs

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/indsex.png)


**Power BI AI Tools**:

**Key Influencers**: We want to Analyze the State condition. So when Country is US, we get all the insights like Amount Pledged, Backers, Category etc. We we click % segment, we get to know detailed info regarding what all parameters are influencing the State to be Successful

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/Capture1.PNG)
![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/Capture1.1.PNG)

**Decomposition Tree**: Here, we Analyze column Pledged & we get detailed information based on Country, Category,Name, Subcategory. Great way to Analyze a certain feature

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/Capture3.PNG)

 - [Data Insights- BI File](https://drive.google.com/file/d/1Rm0NvcOCEskYwXeAn3h5WBSPq7PMtTfG/view?usp=sharing)
 
 - [BI File PDF](https://drive.google.com/file/d/1JlrOy_gCm3Pt9-At2p7K1B99840QfUQI/view?usp=sharing)



## Answering the questions after gathering insights

#### The Core concept behind the KickerStarter Project revolves around few questions and with the help of various python libraires and BI tools like Power BI, we try and solved it. The questions are as follows:

## Question 1
1.Which category has the highest success percentage? How many projects have been successful?

Success for a Kickstarter Project is when the Pledged Amount exceeds Goal Amount which certainly tells that investors are confident about certain projects. Such top 3 category of Projects include Film&Video, Games, Technology

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/Capture4.PNG)

## Question 2

2.What project with a goal over 1,000 USD, had the biggest Goal Completion % (Pledged / Goal)? How much money was pledged?

Project of goal over $1000 USD which had biggest Goal Completion and a good Pledged/Goal Ratio is Product Design SubCategory

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/Capture5.PNG)

## Question 3
3.Can we identify any trends in project success rates over the years?
We can certainly say that there was a boom after 2014 and reached its zenith in 2015 for Successful Projects

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/Capture6.PNG)

## Question 4
4.As an investor, what types of projects should you be looking at to guarantee future success?

As an investor, I would certainly want to invest in projects which have high rate of success. Such projects which have given fruitful results are Games, Design,Technology,Film&Videos

![](https://github.com/saks0106/Data_Analyst_Projects/blob/master/Machine%20Learning%20Project/ScreenShots/Capture7.PNG)

### Feedback & Queries

If you have any feedback or Queries, please reach out to me at sakshemgotekar@gmail.com
