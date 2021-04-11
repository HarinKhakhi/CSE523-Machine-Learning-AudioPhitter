# CSE523-Machine-Learning-AudioPhitter
## This is Machine Learning Project on Genre Classification & Mood Tagging


## Code : 
    Genre_Classification.ipynb  => notebook for predicting genere class
    Mood_Regression.ipynb       => notebook for finding score of perticular mood

## Dataset :
    features_30_sec.csv         => features csv file of 30 sec clip from genres_original's song
    features_3_sec.csv          => features csv file of 3 sec clip from genres_original's song
    Mood_Dataset.csv            => Dataset used to predict score of perticular mood.

## Reports :
    ML_Endsem_Report.pdf        => End sem report.
    ML_Midsem_Report.pdf        => Mid sem report.

## Results :
    ### For Genre Classification:
        SVM_Confusion.png       => Confusion Matrix of SVM Classifier
        LR_Confusion.png        => Confusion Matrix of Logistic Regression
        KNN_Confusion.png       => Confusion Matrix of KNeighbors Classifier

        SVM_Validation.png      => C value vs Accuracy Graph
        KNN_Validation.png      => NNeighbors vs Accuracy Graph

        finaltable.png          => Final Table consisting of all three models data

    ### For Mood Tagging : 
        Cost_Happiness.png      => Cost vs Iterations of Happiness Mood Regression Model
        Cost_Energeticness.png  => Cost vs Iterations of Energeticness Mood Regression Model

        Energeticness.png       => Predictions vs Actual values Graph of Energeticness mood
        Happiness.png           => Predictions vs Actual values Graph of Happiness
