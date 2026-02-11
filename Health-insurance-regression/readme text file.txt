Prerequisites:

You need the following installed:
Python (>=3.7 recommended)

Libraries:

pip install pandas scikit-learn
(Optional but helpful: matplotlib, seaborn, numpy if plotting/evaluation is included later in the notebook.)

Dataset:

The code expects a file called: data_insurance.csv
and it should be placed in /content/ if running in Google Colab, or in the same folder as the notebook if running locally (then change the
path accordingly).

Instructions to Run:

Open Google Colab
Upload the notebook (code.ipynb)
Upload the dataset (data_insurance.csv) to Colab
from google.colab import files
uploaded = files.upload()
Ensure the dataset filename matches exactly (data_insurance.csv)
Run cells in order (Shift + Enter)
Run cells sequentially