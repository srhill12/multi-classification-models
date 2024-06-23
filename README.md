# Multi Classification Models

## Purpose

Examine several datasets and select and perform preprocessing tasks, followed by training the data on multiple classification models before evaluating which one performs the best.

## Part 1: Review Datasets

Review the datasets 

**Binary Classification Datasets**

* Customer churn ([dataset](https://static.bc-edx.com/ai/ail-v-1-0/m13/lesson_3/datasets/customer-churn.csv)) ([info](https://static.bc-edx.com/ai/ail-v-1-0/m13/lesson_3/datasets/customer-churn.names))

* Sports article objectivity ([dataset](https://static.bc-edx.com/ai/ail-v-1-0/m13/lesson_3/datasets/sports-articles.csv)) ([info](https://static.bc-edx.com/ai/ail-v-1-0/m13/lesson_3/datasets/sports-articles.names))

**Multiclass Classification Datasets**

* Letter recognition ([dataset](https://static.bc-edx.com/ai/ail-v-1-0/m13/lesson_3/datasets/letter-recognition.csv)) ([info](https://static.bc-edx.com/ai/ail-v-1-0/m13/lesson_3/datasets/letter-recognition.names))

* Website phishing ([dataset](https://static.bc-edx.com/ai/ail-v-1-0/m13/lesson_3/datasets/phishing.csv)) ([info](https://static.bc-edx.com/ai/ail-v-1-0/m13/lesson_3/datasets/phishing.names))

* Orthopedic patients (normal, disk hernia or spondylolisthesis) ([dataset](https://static.bc-edx.com/ai/ail-v-1-0/m13/lesson_3/datasets/vertebral-column.csv)) ([info](https://static.bc-edx.com/ai/ail-v-1-0/m13/lesson_3/datasets/vertebral-column.names))

## Part 2: Data Preprocessing

1. Determine which of the following preprocessing tasks should be performed on the datasets:

    * `train_test_split()`

    * Scaling (`StandardScaler()` or `MinMaxScaler()`)

    * Encode categorical data (`LabelEncoder()` and/or `OneHotEncoder()`)

      * **Note to Self:** `LabelEncoder()` should be used for target variables and `OneHotEncoder()` should be used for features.

2. Perform the required preprocessing tasks as determined in the previous step.

## Part 3: Model Training and Evaluation

1. Use the following classification models to train with your datasets:

    * Logistic regression

    * Support vector machine (SVM)

      **Note to Self:** choose any kernel, it doesn't have to be `linear`.

    * K-nearest neighbor (KNN)

    * Decision tree classifier

    * Random forest classifier

    * Extremely random trees classifier

    * Gradient boosting classifier

    * Adaptive boosting (AdaBoost) classifier

2. Train the models on the preprocessed data.

3. Evaluate the models using `model.score` on the training and testing data.


## References

*Iranian Churn Dataset*. 2020. UCI Machine Learning Repository. Available: https://archive.ics.uci.edu/dataset/563/iranian+churn+dataset [2023, September 20]. ([CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode))

Slate, D. 1991. *Letter Recognition*. UCI Machine Learning Repository. Available: https://archive.ics.uci.edu/dataset/59/letter+recognition [2023, September 25]. ([CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode))

Rizk,Y. & Awad, M. 2018. *Sports articles for objectivity analysis*. UCI Machine Learning Repository. Available: https://archive.ics.uci.edu/dataset/450/sports+articles+for+objectivity+analysis [2023, September 27]. ([CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode))

Abdelhamid, N. 2016. *Website Phishing*. UCI Machine Learning Repository. Available: https://archive.ics.uci.edu/dataset/379/website+phishing [2023, September 25]. ([CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode))

Barreto, G. & Neto, A. 2011. *Vertebral Column*. UCI Machine Learning Repository. Available: https://archive.ics.uci.edu/dataset/212/vertebral+column [2023, September 25]. ([CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/legalcode))
