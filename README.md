
## Table of Contents

- [About](#about)
- [Project Description](#description)
- [Authors](#authors)

## About <a name = "about"></a>

This is a Machine Learning Project that uses the BBC News Dataset to classify news articles into 5 categories: Business, Entertainment, Politics, Sport, Tech. The dataset can be found [here](http://mlg.ucd.ie/datasets/bbc.html). The project uses the Random Forest Classifier to classify the news articles. The project is written in Python and uses the NLTK library for text processing.

This Project also includes the Text Summarization of the news articles. The Text Summarization is done using the TextRank Algorithm. The TextRank Algorithm is an extractive and unsupervised text summarization technique. The TextRank Algorithm is based on the PageRank Algorithm. The TextRank Algorithm is implemented using the NLTK library.




## Project Description <a name = "description"></a>

### Prerequisites

- Python 3.6 or above
- NLTK Library
- Pandas Library
- Numpy Library
- Scikit-Learn Library
- Matplotlib Library
- Seaborn Library
- Networkx Library

### Installing

- Install Python 3.6 or above from [here](https://www.python.org/downloads/)

All the requirements can be installed using the following command:

```
pip install -r Requirements.txt
```

### Technologies Used

- Language: Python
- Libraries: NLTK, Pandas, Numpy, Scikit-Learn, Matplotlib, Seaborn, Networkx
- IDE: Jupyter Notebook

- Machine Learning Model: Random Forest Classifier, Naive Bayes, XGBoost
- Text Summarization Algorithm: TextRank Algorithm, LexRank Algorithm

- Dataset: BBC News Dataset



### Challenges Faced

- The dataset is not balanced. The dataset has more articles of the Business category and less articles of the Tech category. This can lead to the model being biased towards the Business category. This can be solved by using the SMOTE technique to balance the dataset.

- The dataset has a lot of stopwords. This can lead to the model being biased towards the stopwords. This can be solved by removing the stopwords from the dataset.

- The dataset has a lot of punctuations. This can lead to the model being biased towards the punctuations. This can be solved by removing the punctuations from the dataset.

- The dataset has a lot of numbers. This can lead to the model being biased towards the numbers. This can be solved by removing the numbers from the dataset.


### Improvements

- The dataset can be balanced using the SMOTE technique.

- The dataset can be cleaned by removing the stopwords, punctuations and numbers.

- The dataset can be cleaned by removing the words with length less than 3.



## Contributing

Contributions, issues and feature requests are welcome.



## Authors

- [@Nitish](https://nitishpandey.com.np/)
- [@Masood]()
- [@Vishwa]()
- [@Sanjog]()


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

