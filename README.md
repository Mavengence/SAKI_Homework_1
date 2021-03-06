 <div style="background-color:white">
  <div align="center">
    <img src="https://www.fau.de/wp-content/themes/FAU-Einrichtungen/img/logos/fau-logo-240x65.svg" width="700" height="250">
    <hr>
    <h1 style="color:black">Transaction Classification<h1>
    <h3 style="color:black">Tim Löhr<h3>
  </div>
</div>    

## Background
For my university master course Software Applications with Artificial Intelligence, I received a dataset of bank transfer data with 209 datapoints and 11 features. The features are containing basic transactional information, such as the amount of money, the banking number or usage purpose. The data is provided by Adorsys GmbH.

## Objective
This project aims to quantify how accurately bank transfer data can classify seven different labels. Those labels are for example standard of living or income. Different data from the bank transfer could have an indication for which label this payment aims for. Therefore, I analyses all the features given to us and underdo different preprocessing techniques and combinations, because we have categorical data, numbers and also text.
I try out different combinations with the data and use the naive bayes classifier for the classification task. Furthermore, the dataset is split into a train, test and validation set, because of the slight data imbalance.
In the end, the trained model will be evaluated based on the accuracy and F1 score, because we have a multiclass classification task which is imbalanced. Therefore, only the accuracy score is not sufficient enough to evaluate the result.

### Structure

```

+-- Transaction_Classification.ipynb  
+-- classification_report.pdf            
+-- data.csv                         
+-- requirements.txt                    
+-- README.md
+-- .gitignore              

```
## Links to Ressources

- Transaction_Classification as [iPython](https://github.com/Mavengence/SAKI_Homework_1/blob/master/Transaction_Classification.ipynb)

- Final Report [PDF](https://github.com/Mavengence/SAKI_Homework_1/blob/master/classification_report.pdf)

## Ressources

- NLP for Features: https://towardsdatascience.com/named-entity-recognition-with-nltk-and-spacy-8c4a7d88e7da

- Model building: https://scikit-learn.org/stable/

- F1 Score visualizations: https://www.scikit-yb.org/en/latest/api/classifier/classification_report.html

### Prerequisites

```
The dependencies to this project are stored in the file:
   - requirements.txt

I use python version 3.6.0
```

## Author

* **Tim Löhr** - If you have questions you can contact me under timloehr@icloud.com

## License

This project was done during my course Software Applications with Artificial Intelligence at the Friedrich Alexander University in Erlangen-Nürnberg.
