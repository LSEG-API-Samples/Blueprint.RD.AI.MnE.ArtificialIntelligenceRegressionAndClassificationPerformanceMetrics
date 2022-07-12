# Modelling and Evaluation - Artificial Intelligence regression and classification performance metrics


## <a id="overview"></a>Overview
After we have defined, optimised and validated the AI cores, the last step in the modelling and evaluation phase is evaluating the performance of the built models. As we have discussed there are numerous AI genres and methodologies but all, most of the time, will try to solve two very common problems. The first one is to predict a future value of a target variable that belongs in the continuous space Z calles regression and the later, a categorical future value amongst a collection of possible ones called classification. There are indeed, more complex problems than those two, however again, most of the times, can be seggregated into multiple sub-problems that fall into the previous two categories. Furthermore a significant part of these use cases fall under the supervised learning AI context.

Regardless of the category, we will usually be designing and training a few AI cores before we decide on the best one to push into production. We therefore need the quantitative means that will enable to decide which core is the best to use. The evaluation metrics available are different depending on the genre of the AI problem at hand and in this article we will be discussing available regression and classification AI evaluation metrics.  

## <a id="disclaimer"></a>Disclaimer
The source code presented in this project has been written by Refinitiv only for the purpose of illustrating the concepts of creating example scenarios using the Refinitiv Data Library for Python.

***Note:** To [ask questions](https://community.developers.refinitiv.com/index.html) and benefit from the learning material, I recommend you to register on the [Refinitiv Developer Community](https://developers.refinitiv.com)*

## <a name="prerequisites"></a>Prerequisites

To execute any workbook, refer to the following:

- A Refinitiv Desktop license (Refinitiv Eikon or Refinitiv Workspace) that has API access 
- Tested with Python 3.7.13
- Packages: [scikit-learn](https://pypi.org/project/scikit-learn/), [refinitiv.data](https://pypi.org/project/refinitiv-data/)
- RD Library for Python installation:  '**pip install refinitiv-data**'


  
## <a id="authors"></a>Authors
* **Marios Skevofylakas**
