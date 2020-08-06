# Topic Modeling Using LDA (Latent Dirichlet Allocation)

![LDA](https://3.bp.blogspot.com/-5ZSDw3tP1ho/V1WU4aNqPbI/AAAAAAAAAP0/5phmpChHY_IoTyVztSxZIapC1LYqKpVoQCLcB/s1600/lda.jpg)<br/>
<b>Latent Dirichlet Allocation (otherwise known as LDA) is a form of unsupervised learning that views documents as bags of words. LDA works by first making a key assumption: the way a document was generated was by picking a set of topics and then for each topic picking a set of words.</b> 
* Source: <a href=https://towardsdatascience.com/lda-topic-modeling-an-explanation-e184c90aadcd>LDA Topic Modeling</a>
## Dataset <br/>
</t> The dataset contains details about research papers and related metadata. Since these papers are collected irrespective of their field, our goal as data scientist is to use this dataset to create a topic modeling (which will allows us to have a better intuition about distribution of topics in research papers). 

## Process<br/>
1. Import libraries and Read data 
 2. Drop all irrelevant columns from dataset<br/>
  3. Create a text cleaning pipeline (Remove pucntuations, convert text into lower case, remove stop words and remove uni-character letter and symbols)<br/>
  4. Create a word cloud to understand the most frequest to least frequent set of words<br/>
  5. Using Count Vectorizer and Matplotlib we will plot 10 highest frequest words (uni-grams) [we can select bi-grams and tri-grams as well]<br/>
  6. Utilize LDA algorithm to extract 2 things:<br/>
    <t> 6.1. No of topics<br/>
        6.2. No of words in each topic <br/>
    </t>
  7. Using powerful visualization library <b>PyLdavis</b> we will visualize topic's distribution along with frequest words in each topic.<br/>
## Recommended Articles
* Great article to read <a href=https://towardsdatascience.com/end-to-end-topic-modeling-in-python-latent-dirichlet-allocation-lda-35ce4ed6b3e0>Click Here</a>
## Reference 
* <a href=https://towardsdatascience.com/end-to-end-topic-modeling-in-python-latent-dirichlet-allocation-lda-35ce4ed6b3e0>Topic Modeling in Python</a>
