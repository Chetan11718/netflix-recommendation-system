For execution of the code load the csv from the dataset provided in the folder.
Import all this libraries  

Preprocess the data


import numpy as np
import pandas as pd
from pandas import DataFrame
from collections import Counter

import seaborn as sns
import matplotlib.pyplot as plt
import plotly.express as px
%matplotlib inline

sns.set_theme(style="darkgrid")



import os
for dirname, _, filenames in os.walk('/kaggle/input'):
    for filename in filenames:
        print(os.path.join(dirname, filename))



Then lead the csv file using
df = pd.read_csv("/filename")

Then just run all code by clicking at each cell.

