This repository includes the code for my PSY 341K project: "Parental Perspectives Unveiled: A Comparative LIWC Analysis on Analytic Thinking, Emotion, and Well-Being Among New Fathers and New Mothers on Reddit"

Download 'PSY341K-SIMULATED.DATA.csv' to test the code.

# Required Imports

To run the code successfully, ensure you have the following Python libraries installed:

```python
import pandas as pd
import numpy as np
from scipy.stats import t
from wordcloud import WordCloud
import matplotlib.pyplot as plt
import re
import nltk
from nltk.corpus import stopwords
from collections import Counter
from nltk import word_tokenize
from nltk.util import ngrams
