# RSI Backtest vs Simple Buy and Hold Strat

The data and other related files are not available for uploading due to privacy reason. Only the outputs are available.
`The codebase is for reference purpose only`.

## Installation
- Required: `pandas`, `openpyxl` `jupyter`. If you already have these packages on your machine then the project is ready to run without the need of installing any additional package.

### Step 1: Navigate to the Project Folder
- Navigate to the main folder where requirements.txt if located

### Step 2: Set Up a Virtual Environment (optional but recommended)

Create a new virtual environment by running

`python3 -m venv venv`

OR

`python -m venv venv`

Activate the virtual environment:
- On Windows:

  `.\venv\Scripts\activate`
- On macOS and Linux:

  `source venv/bin/activate`

### Step 3: Install Dependencies

Install the required Python packages with pip:

`pip install -r requirements.txt`

## Folder Structure

```bash
answers                                -> Folder containing all answer files and notebooks
|
├── NAV                       
|   └── NAV.ipynb             
|
├── backtest                           
|   ├── generated_data                 -> Subfolder for generated data files with RSI calculated
|   |   ├── M1W00HC.csv                -> M1W00HC data
|   |   ├── NBI.csv                    -> NBI data
|   |   ├── SPX.csv                    -> SPX data
|   |   └── XBI.csv                    -> XBI data
|   |
|   ├── trades                         -> Subfolder for generated trade data 
|   |   ├── M1W00HC_trades.csv         -> M1W00HC trade data
|   |   ├── NBI_trades.csv             -> NBI trade data
|   |   ├── SPX_trades.csv             -> SPX trade data
|   |   └── XBI_trades.csv             -> XBI trade data
|   |
|   ├── backtest.txt                -> Output data file for the backtest
|   └── backtest.ipynb             -> Jupyter notebook for the backtest
|
|
|
requirements.txt                       -> requirements.txt to start the virtual env
|
README.md                              -> README file
```
--------

