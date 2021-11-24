# Statistical-Machine-Learning-Project

## FICO Dataset

We have at our disposal several fairness-related datasets in the package [Responsibly](https://docs.responsibly.ai), including the FICO dataset that was used in the paper. Moreover, this package and this [repository](https://github.com/fairmlbook/fairmlbook.github.io) have already some method implemented.

<br />

The folder [Data]() in this repository also contain the FICO dataset in .pkl file. On python, we can upload this dataset with the followings lines of code :
```
import pickle
a_file = open("Data/FICO.pkl", "rb")
FICO_download = pickle.load(a_file)
a_file.close()
```

The FICO dataset is a dictionary which contain some pandas dataframe, we can find more information on the structure of this dataset [here](https://docs.responsibly.ai/notebooks/demo-fico-analysis.html)
