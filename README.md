# Delayma Preprocessing(Organized)
Preprocessing the data for training the ML model

## Setup

Create a virtual environment and install the dependencies
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```
Download data by running  `data_retrieval.py`
```bash
python data_retrieval.py
```

## Structure of the `data` directory
```
data
 ┣ 2gb_dataset
 ┃ ┣ processed
 ┃ ┗ unprocessed
 ┗ 4gb_dataset
 ┃ ┣ processed
 ┃ ┗ unprocessed
 ```

 