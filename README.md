# **COVID-19 Open Research Dataset: Topic Modelling**
![image](https://user-images.githubusercontent.com/76100096/132978989-41e61892-4dc1-4048-868b-f4be92169939.png)


COVID-19 Open Research Datasets contain a lot of data that we can take as our insight for our project. In this project, I am taking insight about **Topic Modelling**.

**Topic Modelling** is an approach on getting topic from articles on the dataset. Since most of this data talks about COVID-19, this model only could predict topic that related
to COVID-19, Pandemic, and etc. 

In this project, I am using **Natural Language Processing** approach with **Unsupervised Learning** model such as **Latent Dirichlet Allocation**, **BERT embedding**, 
**Combination LDA + BERT**, and **BERTopic** for the final model since it satisfy the highest **Coherence Score** for over 51% as my evaluation metrics. This coherence score also help
the clustering visualization, which in this project, I am using **T-SNE** and **K-Means** for Clustering.

This model could predict the topic by given **Abstract** from articles that related to COVID-19.

## Acknowledgements
This dataset was taken from Kaggle https://www.kaggle.com/allen-institute-for-ai/CORD-19-research-challenge
