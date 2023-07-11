# Breast-Cancer-Classification-Machine-Learning-and-its-Applications

Breast-Cancer-Classification is a web application designed to classify breast cancer using machine learning techniques. It provides separate pages for users and researchers, allowing them to interact with the application in different ways.

## Instructions

* The user page allows individuals to input relevant information about a breast cancer case and receive a classification result.
* The researcher page is intended for individuals involved in breast cancer research. It provides additional functionality for analyzing and exploring the dataset.

**The necessary packages are:**
  * Tensorflow
  * Keras
  * Flask

## Steps

1. You can see the code for training the model in this [notebook](https://github.com/ArunAdhithiya/Breast-Cancer-Detection/tree/main/training).

2. Before running the code for training the model, you need to have the **dataset** present in this [DATA](https://github.com/ArunAdhithiya/Breast-Cancer-Detection/tree/main/DATA) folder.

3. This repository also consists of already trained weights for this model which you can find [here](https://github.com/ArunAdhithiya/Breast-Cancer-Detection/blob/main/src/model_ann_new_weights.h5).


### Running the application:

1. Get the source code on your pc via git.

```shell
  git clone https://github.com/ArunAdhithiya/Age-and-Gender-Prediction.git
```

2. Create a virtual environment to install the required dependencies of the application.

```
  virtualenv venv
```

3. Activate the virtual environment (You have to activate it every time you are working on project).

```
  For mac users:

    source venv/bin/activate  

  For windows users:

    .\venv\Scripts\activate

  For Linux users:

    source venv/bin/activate
```

4. Now, install python dependencies.

```
  pip install -r requirements.txt
```

5. Now, navigate to the **src** directory (containing the **app.py** file).

6. Run following command:

```
  python app.py
```

7. Application is ready for use. You can run it at [http://localhost:80/./homepage](http://localhost:80/./homepage).
