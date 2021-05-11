<div style="https://www.fau.de/wp-content/themes/FAU-Einrichtungen/img/logos/fau-logo-240x65.svg">
  <div align="center">
    <hr>
    <h1 style="color:black">Transaction Classification<h1>
  </div>
  <hr>
</div>

## Objective
Using a real dataset from the master course `Software Applications with Artificial Intelligence`, I try to predict based on bank transfer data, how accurately I can predict a given label. For this project, I analyise all the features given to us and underdo different preprocessing techniques, because we have categorical data, numbers and also text.
I try out different combinations with the data and use the naive bayes classifier for the classification task.
Furthermore, the dataset is split into a train, test and validation set, because of the slight data imbalance.
In the end, the trained model will be evaluated based on the accuracy and F1 score, because we have a multiclass classification task which is imbalanced. Therefore only the accuracy score is not sufficient enough to evaluate the result.

### Structure

```

+-- Transaction_Classification.ipynb  
|
+-- classification_report.pdf
|              
+-- data.csv                         
+-- requirements.txt                    
+-- README.md
+-- .gitignore              

```
## Links to Ressources

- Transaction_Classification as [iPython](https://mad-srv.informatik.uni-erlangen.de/MadLab/industry-4.0/seminar-i4.0/ss2020/anomaly-detection-with-neural-network-in-time-series-data/-/blob/master/Code/Notebooks/Machine_Learning.ipynb)

- Final Report [PDF](https://mad-srv.informatik.uni-erlangen.de/MadLab/industry-4.0/seminar-i4.0/ss2020/anomaly-detection-with-neural-network-in-time-series-data/-/blob/master/Paper/L%C3%B6hr_Tim_MADI40SS20_final_presentation.pdf)

## Ressources

- NLP for Features: https://towardsdatascience.com/named-entity-recognition-with-nltk-and-spacy-8c4a7d88e7da

- Model building: https://scikit-learn.org/stable/

- F1 Score visualizations: https://www.scikit-yb.org/en/latest/api/classifier/classification_report.html

### Prerequisites

```
The dependencies to this project are stored in the file:
   - requirements.txt

I use python version 3.7.4
```

## Author

* **Tim Löhr** - If you have questions you can contact me under timloehr@icloud.com

## License

This project was done during my course Software Applications with Artificial Intelligence at the Friedrich Alexander University in Erlangen-Nürnberg.
