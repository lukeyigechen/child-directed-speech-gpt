# Age-Sensitive Generative Language Model for Child-Directed Speech

The repository contains the scripts that preprocess the data from the [CHILDES English MacWhinney Corpus](https://childes.talkbank.org/access/Eng-NA/MacWhinney.html) and further pre-train the `gpt2` model and fine-tune the `bert-base-uncased` model for child-directed speech. 

The notebook is suitable for Colab uses (assuming the datasets are stored in the user's drive when mounting). Alternatively, please place the MacWhinney Corpus into the working directory, and run the following to install the required packages. 

``` bash
pip install transformers
pip install datasets
```
