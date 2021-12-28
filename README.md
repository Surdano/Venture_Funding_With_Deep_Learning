# Venture_Funding_With_Deep_Learning

![Image of brain neural network.](https://images.theconversation.com/files/154352/original/image-20170126-23840-1mo1ycx.jpg?ixlib=rb-1.1.0&q=45&auto=format&w=1200&h=675.0&fit=crop)

---

This is a program that creates and compares binary classification models using deep neural networks, which predicts whether Alphabet Soup funding appliants will be successful.

---
## Technologies

This program uses [Python 3.7](https://www.python.org/) along with the following packages:

[Jupyter Lab](https://jupyter.org/install)

[Pandas](https://pandas.pydata.org/)

[hvplot](https://hvplot.holoviz.org/) 

[sklearn](https://scikit-learn.org/)

[tensorflow](https://www.tensorflow.org/)

[Keras](https://keras.io/)

---
## Installation Guide
The dependencies needed to use the anaylzer are:

```python
import pandas as pd
from pathlib import Path
import tensorflow as tf
from tensorflow.keras.layers import Dense
from tensorflow.keras.models import Sequential
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import StandardScaler,OneHotEncoder
```
---
## Usage

If you have Tensorflow installed on your local computer, launch Jupyter Lab with the file: 
```python
venture_funding_with_deep_learning.ipynb
```
If your computer uses the Apple M1 chip and are unable to install Tensorflow on your local computer, utilize the Google Colab file:
```python
GC_venture_funding_with_deep_learning.ipynb
```
Once the program starts running, it will take you through building deep learning models that you can compare to maximize accuracy.

---
## Contributors

This starter code was created from © 2020 - 2021 Trilogy Education Services, a 2U, Inc. brand. 

Additional code was added for full analysis by Thomas Leahy, thomasleahy6@gmail.com

---
## License

MIT Licence

2021 Thomas Leahy