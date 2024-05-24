# Starbuck Project


A Blog post for this project is [here]. 


### Description
This project is to analyse the data set contains simulated data that mimics customer behavior on the Starbucks rewards mobile app.
In this project, I am pretty interesed to target the customers who has successfully affected by the offer based on their profile. I am also interested to find out which offer channels and offer type works best.
So my research question for this project is the following 3:

* #### Which channel works best for sending offers?
* #### Which type offer is the most effective (i.e customer make most transcations after view the offer)
* #### How well are different machine leaning methods in classifing targeted customers?

### 1.Data sets

The data is contained in three files:

* portfolio.json - containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - demographic data for each customer
* transcript.json - records for transactions, offers received, offers viewed, and offers completed

### 2.Methods
For the first 2 questions, I will use visualization and numbers(tables) to find out. For the last question, I will use 4 different classification models to find out. **Exciting coding trips begin!!!**

### 3. About notebooks
The associate notebook for the project contain 4 sections:
* #### Explore and prepare data
> 1. Explore data
> 2. Clean data
> 3. Visualize data
* #### Model data
> 1. Preprocessing data for models
> 2. Classification using logic regression
> 3. Classification using LDA
> 4. Classification using QDA
> 5. Classification using KNN
* #### Results discussion
* #### Conclusion and futher improvement


### 4. Questions and Findings
* **Question1: Which channel works best for sending offers?**
>The 'social' channel has the hightest view rate. So I will conclude the social channel is the best to send out offers if we want to the offer to be viewed.

* **Question2:Which type offer is the most effective?**
>The discount offers has highest transaction rate after it has been viewed by the customer.

* **Question3:How well are different machine leaning methods in classifing targeted customers?**
>QDA has the highest prediction accuracy at 65%. But since our data is limited, the accuracy of the model is not very high.

### Acknowledgement:

#### Files in this repo:
* portfolio.json - dataset containing offer ids and meta data about each offer (duration, type, etc.)
* profile.json - dataset containing demographic data for each customer
* transcript.json - dataset containing records for transactions, offers received, offers viewed, and offers completed
* `Starbucks_Capstone_notebook.ipynb`: Notebook containing data analysis
* `test_Starbucks.ipynb`: Draft notebook for prepare for the project 

#### Libraries:
* numpy == 1.25.2
* pandas == 2.0.3
* matplotlib == 3.7.1
* seaborn == 0.13.1
* scikit-learn == 1.2.2

### References:
* [ISLP Charpter 4 exercise 10 solution](https://botlnec.github.io/islp/sols/chapter4/exercise10/)
* solution notebook for ISLP CH4 create by Sarah Guo for problem 4.16

