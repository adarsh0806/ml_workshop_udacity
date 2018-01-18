# GAIC 2018

## Install

Make sure you have Python 3 installed, preferably using Anaconda. Then run the following command to install required packages:

```bash
pip3 install -r requirements.txt
```

## Run

Run Jupyter and open the notebook for your desired lab:

```bash
jupyter notebook
```

## Data for tutorial notebooks

To avoid having to fetch datasets used in these notebooks, copy all the directories under `data/` (e.g. `.keras`, `nltk_data`, `scikit_learn_data`) to your user home directory (e.g. `/Users/alice/` or `C:\Users\Bob\`). If these directories already exist, just copy the respective content into them.

You can use the `rsync` utility to perform this task, if available on your system:

```bash
rsync -av .keras nltk_data scikit_learn_data ~/
rsync -av data/ ~/
```
