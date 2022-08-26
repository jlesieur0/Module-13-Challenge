# Module-13-Challenge - Venture Funding with Deep Learning#



This exercise on building Deep Learning Models demonstrates usage of the StandardScalar, OneHotEncoder, and test_train_split packages within scikit-learn. These packages paired with the Dense, and Sequential Keras packages within Tensorflow allow one to design a neural network from reduced data and analyze the model's efficacy. This could be due to the use of the 'relu' function for the output layer. However, every attempt at using the 'sigmoid' function was unsuccessful. With more time, I would investigate this issue further. 

---

## Discussion

While 4 models were successfully created, none of them proved to yield favorable results. The first model is actually not shown in this notebook. After building the first alternate model, the accuracy and loss did not improve. So, categorical columns were removed to lessen any confusion by the model. This helped marginally. Then, for the next two alternate models, the number of hidden layers were adjusted. 

---

## Technologies

This project leverages python 3.10 with the following packages:

* [pandas](https://github.com/pandas-dev/pandas) - For available packages within pandas.

* [tensorflow](https://www.tensorflow.org/api_docs/python/tf) - For available packages within tensorflow.

* [tf.keras](https://www.tensorflow.org/api_docs/python/tf/keras) - For available packages within tf.keras.

* [pathlib](https://github.com/matplotlib/matplotlib) - For available packages within matplotlib.

* [sklearn](https://scikit-learn.org/stable/) - For available packages within sklearn.

* [jupyterlab](https://github.com/jupyterlab/jupyterlab) - For packages within jupyter lab.

---

## Installation Guide

This application requires you first install the following dependencies to run correctly.

```python
  pip install pandas
  pip install scikit-learn
  pip install --upgrade tensorflow
```

```jupyter lab
  conda install jupyterlab
```

---

## Usage

To use the crypto investments tool simply clone the repository and run the **crypto_investments.ipynb** with:

```jupyterlab
python venture_funding_with_deep_learning.ipynb
```

Upon launching the Deep Learning notebook, you can see the reduction of the original data, and how it is manipulated to fit a keras model.

---

## Contributors

***Brought to you by World Reknowned Financial Advising Team at LeSieur Financial***

---

## License

### *LICENSE PENDING*