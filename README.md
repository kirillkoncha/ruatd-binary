### [Russian Artificial Text Detection Dialogue Shared task](https://www.kaggle.com/c/ruatd-2022-bi/) 
##### 8th place out of 30 with 81% accuracy score
#### [Project presentation](https://docs.google.com/presentation/d/1sWbo6Toc60kEPzwrjAAK4qzuVdgNHaIeGA9yuKpVq8M/edit?usp=sharing)
#### Description of code files
* logreg.ipynb -- Logistic Regression + TF-IDF with multiple features; uses [data](https://drive.google.com/file/d/1bW0NiUSqriUNxwFd4ToQIPssBOl-gDcQ/view?usp=sharing) with annotated keywords scores (Min and Max) from RAKE
* frozen.ipynb -- BERT with frozen layers
* ELMO.ipynb -- Classification with ELMO model (TensorFlow)
* ROBERTA -- Classfication with ROBERTA
* ruatd-rubert-mixed-features.ipynb -- Rubert model with text length implementation
* rubert-conversational-with-freezing.ipynb -- rubert conversational with 4 frozen layers

and some more notebooks with models were used, but there were mostly some parameters changed...

#### Data analysis
[Colab notebook](https://colab.research.google.com/drive/1gShXlB-_qjmLzNr32meqEuWQuVoDWvZk?usp=sharing)

For comments on Data analysis please see our presentation.
