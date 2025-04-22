# BERT Transfer Learning Sentiment Analysis

This repository is a study on the efficacy of transfer learning using BERT for sentiment analysis.
This project was made for the Rutgers Intro to Data Science final project.

## Developing

This repository requires Python 3.12, since TensorFlow only supports versions 3.9 - 3.12.

It's recommended to use a [Python virtual environment](https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/) to avoid package conflicts with your global Python packages.
First, create a virtual environment.

```bash
python -m venv .venv
```

Then, activate the virtual environment, which causes any packages you install to be installed locally, as well as letting Python know to look for packages locally.

```bash
.venv\Scripts\activate
```

Finally, make sure to install the packages from the `requirements.txt`

```bash
python -m pip install -r requirements.txt
```

To exit the virtual environment, run

```bash
deactivate
```
