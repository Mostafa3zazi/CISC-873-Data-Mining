# CISC-873-DM-Data-Mining
This repo contains the solutions to Kaggle competitions from the Data Mining course from queen’s university mater degree program.
> Each notebook contains: Problem formulation, Data inspecting, Data Preprocessing Trials to find the best solution, Thoughts and observations for trials and comments on results. 
## CISC-873-DM-F22-A1: Wish.com Product Rating Prediction
In this assignment, you will be working with a tabular dataset. The dataset is not clean, and you will need some preprocessing depending on the models of your choice. The dataset is the wish.com product dataset. We collected the data combined with some available data. Some nosies are added to the dataset. The goal is to predict the product ratings given the other features known for a product on Wish.com. Ratings are in categories from 1 to 5. For one product, the higher the rating is, the more the customers like the product. In this way, when you have a new product to be put on wish.com, you can estimate how likely people will like your product, without actually listing out there.<br>
comptition link : https://www.kaggle.com/competitions/cisc-873-dm-f22-a1

## CISC-873-DM-F22-A2: Whether a first date will lead to a relationship
In this assignment, we are going to predict the outcome of a specific speed dating session based on the profile of two people, so we can implement a recommendation system to better match people in speed dating events. We did have another online dating dataset (Tinder-like) but that one is super dirty which requires extensive cleaning, so we do this one instead. This is a binary classification task. Given a data sample (information about the dating session), we are going to predict the probability (0-1, float) that the dating session will lead to a successful match.
The dataset is clean, but has a lot of missing values. The strategy for missing value replacement has to be tuned. Also, as you can guess, this dataset is highly unbalanced (mostly unmatched). The idea of this assignment is to treat the complete workflow from data preprocessing to model training as a single pipeline, and search for the hyperparameters for this pipeline.<br>
comptition link : https://www.kaggle.com/competitions/cisc-873-dm-f22-a2


## CISC-873-DM-F22-A3: Fake Reddit Prediction
False information on the Internet has caused many social problems due to the raise of social network and its role in different domains such as politics. In this assignment, we are going to predict if a specific reddit post is fake news or not, by looking at its title. The data is raw (contains various forms of words) so it is up to you on what text preprocessing techniques to be applied.<br>
comptition link : https://www.kaggle.com/competitions/cisc-873-dm-f22-a3

## CISC-873-DM-F22-A4: Airbnb price category prediction
One of the biggest problems when people prepare to post a new listing on airbnb is, how much should one ask for? Of course the most intuitive way is to check how other similar postings price their apartment/house. So in this assignment, we are going to predict the listing price based on the listing characteristics 🔥🔥, in this way to optimize user experience and lower the bar to be a new host😍 !
Predicting the actual price could be simple (well you can just go search online 👍), so we cut the pricing into three different bins for classification 😂. For each listing, we recommend a pricing range to the new host rather than a fix price (how nice is that!). So we define three categories: beginner, plus, premium based on the created listing. Respectively we use 0, 1, 2 to denote these three categories.
The dataset contains listings of different areas in Montreal during 2019. It comes with rich information for each listing, including a link to the thumbnails etc. As discussed in the last lecture, we will follow a multi-objective (multi-task) multi-modality solution.<br>
comptition link : https://www.kaggle.com/competitions/cisc-873-dm-f22-a4
