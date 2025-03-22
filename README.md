# hERG Inhibition Prediction
## Project Overview
Drug discovery is a costly and time consuming process with a lare percentage of candidate compounds failing in latet stages due to safety concerns. Therefore to improve drug safety and reduc later stage failure, early screening for hERG inhibition is essential.
The aim of this project is to develop a machine learning model that predicts hERG inhibition using a molecules SMILES representation as input. By leveraging computational approaches, this model will help filter out unsafe candidates at an early stage of drug development ultimately accelerating its process and reducing costs

## Installation
```bash
pip install PyTDC rdkit pandas numpy scikit-learn matplotlib seaborn
```

## Dataset Details
- **Source:** [Therapeutics Data Commons (TDC)](https://tdcommons.ai/)
- **Dataset:** `tdc.multi_pred.Tox(name="hERG")`
- **Data Format:** CSV

| Column   | Description                                      |
|----------|--------------------------------------------------|
| Drug_ID  | Unique identifier for the drug                  |
| Drug     | Molecular structure in SMILES format            |
| Y        | Target (1 = inhibits hERG, 0 = does not inhibit) |

