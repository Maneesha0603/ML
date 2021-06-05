# ML                                                   Poem and Novel Classifier

PROBLEM STATEMENT



Simple classifier capable of distinguishing with a relevancy score between poems and novel summaries.


The test data will contain excerpts which the classifier has to predict as a "poem" or "novel"

If a garbled or unresolvable text is encountered it has to be outlined as "NA"

Libraries required:

import pandas as pd
import numpy as np
import math
import matplotlib.pyplot as plt
import warnings
from sklearn.model_selection import train_test_split
from sklearn.feature_extraction.text import CountVectorizer
from sklearn.linear_model import LogisticRegression
from sklearn.metrics import classification_report
from nltk.tokenize import word_tokenize
from nltk.corpus import stopwords



